# neovim
Neovim with Terraform/Terraform Autocomplete Support

# Requirements 

For a working terraform autocomplete you even need to install  ruby and nodejs plugin

nvim (We use appimage https://appimage.org/ version)
```
**sudo curl -O /usr/local/bin/nvim https://github.com/neovim/neovim/releases/download/v0.4.3/nvim.appimage**

**sudo chmod 755 /usr/local/bin/nvim**

**sudo pip2 install --upgrade neovim sexpdata websocket-client**

**sudo pip3 install --upgrade neovim sexpdata websocket-client**

**sudo gem install json neovim**

**sudo npm install -g neovim**

**curl -fLo ~/.config/nvim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim**

**curl -O /tmp/terraform.zip https://releases.hashicorp.com/terraform/0.12.16/terraform_0.12.16_linux_amd64.zip**

**unzip /tmp/terraform.zip**

**sudo mv terraform /usr/local/bin/**

**sudo chmod 755 /usr/local/bin/terraform**


# Final step
**nvim**

**:UpdateRemotePlugins**
```





