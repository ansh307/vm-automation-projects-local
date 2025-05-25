## 🚀 How to Use

### 🔄 Clone the Repository

```bash
git clone https://github.com/yourusername/vagrant-projects.git
cd vagrant-projects
```

### ▶️ Launch Any Project

Choose a folder and run the following inside it:

```bash
vagrant up
```

### 💻 SSH into a VM

```bash
vagrant ssh
```

### 🛑 Stop the VM

```bash
vagrant halt
```

### 🧹 Destroy the VM

```bash
vagrant destroy -f
```

---

## 🔍 Example Vagrantfile Snippet (IP, RAM, CPU)

```ruby
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/jammy64"
  config.vm.network "private_network", ip: "192.168.56.10"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "1024"
    vb.cpus = 2
  end
end
```

lets goo🔥🔥🔥
