1. To run Hadoop: first set Java Home
export JAVA_HOME=/Library/Internet\ Plug-Ins/JavaAppletPlugin.plugin/Contents/Home/
echo ${JAVA_HOME}


2. Test using: 
cd /Users/chandana/Documents/Hadoop/hadoop-2.6.5
bin/hadoop version
o/p:
Hadoop 2.6.5
Subversion https://github.com/apache/hadoop.git -r e8c9fe0b4c252caf2ebf1464220599650f119997
Compiled by sjlee on 2016-10-02T23:43Z
Compiled with protoc 2.5.0
From source with checksum f05c9fa095a395faa9db9f7ba5d754
This command was run using /Users/chandana/Documents/Hadoop/hadoop-2.6.5/share/hadoop/common/hadoop-common-2.6.5.jar



3. Hive exports:
export HIVE_HOME=/Users/chandana/Documents/Hadoop/apache-hive-2.3.2-bin
export PATH=$HIVE_HOME/bin:$PATH
export HADOOP_HOME=/Users/chandana/Documents/Hadoop/hadoop-2.6.5









Basic Linux commands:

pwd
cd
ls -l
ls -ltr
ls
. -> current directory
.. -> directory above
cd ..	

chown -> Change owner of the file/dir
chmod -> Change permission of the file/dir




