# kali-solved

# could not get lock /var/lib/dpkg/lock [ SOLVED ]


``
sudo rm /var/lib/apt/lists/lock
``

``
You may also need to delete the lock file in the cache directory
``

``
sudo rm /var/cache/apt/archives/lock
``

``
sudo rm /var/lib/dpkg/lock
``
