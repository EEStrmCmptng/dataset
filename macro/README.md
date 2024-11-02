```
sudo dnf -y update
sudo dnf upgrade --refresh
sudo dnf system-upgrade download --releasever=40
sudo dnf clean packages
sudo dnf system-upgrade reboot

sudo dnf install -y java-11-openjdk.x86_64 iperf iperf3-devel htop git python3-pip unzip net-tools p7zip nload iotop iftop chrony cifs-utils samba nvme-cli nfs-utils wget emacs
```