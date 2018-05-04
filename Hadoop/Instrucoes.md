1. Abra uma consola no terminal do Cloudera VM e crie/copie os ficheiros .py
2. Tornar os ficheiros executaveis
chmod +x wordcount_mapper.py
chmod +x wordcount_reducer.py
3. Crie alguns dados sobre os quais o Hadoop irá trabalhar
echo "A long time ago in a galaxy far far away" > /home/cloudera/testfile1
echo "Another episode of Star Wars" > /home/cloudera/testfile2
4. Crie um diretorio no sistema de ficheiros HDFS:
hdfs dfs -mkdir /user/cloudera/input
5. Copie os ficheiros do sistema local para o sistema de ficheiros do HDFS
hdfs dfs -put /home/cloudera/testfile1 /user/cloudera/input
hdfs dfs -put /home/cloudera/testfile2 /user/cloudera/input
6. Visualize os ficheiros no HDFS
hdfs dfs -ls /user/cloudera/input
7. Corra o exemplo WordCount com os inputs e outputs definidos
hadoop jar /usr/lib/hadoop-mapreduce/hadoop-streaming.jar \
   -input /user/cloudera/input \
   -output /user/cloudera/output_new \
   -mapper /home/cloudera/wordcount_mapper.py \
   -reducer /home/cloudera/wordcount_reducer.py
8. Verifique os resultados:
hdfs dfs -cat /user/cloudera/output_new/part-00000
9. Verifique o diretorio de output:
hdfs dfs -ls /user/cloudera/output_new
10. Verifque os conteudos dos ficheiros
hdfs dfs -cat /user/cloudera/output_new/part-00000
