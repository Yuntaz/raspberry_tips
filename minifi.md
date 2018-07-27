# Minifi on Raspberry

Here is a list of steps to install Minifi. 

## Java
We need to install is the Oracle JDK 8.

```
sudo apt-get install oracle-java8-jdk
```

## Install MiniFi

We are going to install MiniFi on the Raspberry Pi. First download the the MiniFi release.
You can find the last version at [https://docs.hortonworks.com](https://docs.hortonworks.com) and you can check the repositories on the release notes.
For this example, we are using HDF 3.1.2 [https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.1.2/bk_release-notes/content/ch_hdf_relnotes.html](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.1.2/bk_release-notes/content/ch_hdf_relnotes.html)

### Download
```
sudo su
cd /opt
wget http://public-repo-1.hortonworks.com/HDF/3.1.2.0/minifi-0.4.0.3.1.2.0-7-bin.zip
wget http://public-repo-1.hortonworks.com/HDF/3.1.2.0/minifi-toolkit-0.4.0.3.1.2.0-7-bin.zip
```
### Unzip
```
unzip minifi-0.4.0.3.1.2.0-7-bin.zip
rm minifi-0.4.0.3.1.2.0-7-bin.zip
unzip minifi-toolkit-0.4.0.3.1.2.0-7-bin.zip
rm minifi-toolkit-0.4.0.3.1.2.0-7-bin.zip
```
