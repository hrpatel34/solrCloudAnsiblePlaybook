# solrCloudAnsiblePlaybook
This playbook can be used to install Solr in cloud setup with zookeeper ensamble.

You can install multiple instances of zookeeper and solr on same host. 

Before you use it, doenload zookeeper, java 8 and solr source. 

Save zookeeper source in install_zookeeper/files. Update version and source filename in hosts/groups_var/zk_hosts.

Save Java 8 source in install_java/files. Update version and source filename in hosts/groups_var/all_hosts.

Save solr source in install_solr/files.  Update version and source filename in hosts/groups_var/solr_hosts.

If you are planning to use DIH and oracle as database, you can download orarcle driver file and save it in solr_install/file. 

Once saved, remove comment for odbc installation from solr_install/tasks/main.yml 
