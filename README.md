# vagrant-chef-wordpress

A shortcut to a Wordpress dev environment on a Vagrant VirtualBox provisioned with Chef. Updated to support Vagrant 2 (1.2) configuration.

## Usage

One: Clone this repository.

```
git clone https://github.com/Version2beta/vagrant-chef-wordpress.git
```

Two: Vagrant up, yo.

```
cd vagrant-chef-wordpress
```

* If needed, download & install virtual box 4.2.x: http://www.virtualbox.org/wiki/Downloads
* If needed, Download & install vagrant latest: http://downloads.vagrantup.com/

From the terminal (inside vagrant-chef-wordpress dir):

```
vagrant up
```

* If needed, ```vagrant ssh``` (if on windows: http://vagrantup.com/v1/docs/getting-started/ssh.html)

This takes almost 5 minutes on my laptop.

Three: Configure your blog at [http://localhost:8000/wp-admin/install.php](http://localhost:8000/wp-admin/install.php).

