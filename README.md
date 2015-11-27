#### install
    # yum install rpm-build  

#### change to normal user
    # su - normal_user
    $ mkdir -p ~/rpmbuild/{BUILD,RPMS,SOURCES,SPECS,SRPMS}
    $ echo '%_topdir %(echo $HOME)/rpmbuild' > ~/.rpmmacros

