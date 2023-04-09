### Guidelines

- stable-diffusion-webui官网
https://github.com/AUTOMATIC1111/stable-diffusion-webui

- 模型
https://cyberes.github.io/stable-diffusion-models/

- 前置依赖
  - CUDA驱动 https://developer.nvidia.com/cuda-downloads?target_os=Windows&target_arch=x86_64
  - Git程序 https://git-scm.com/downloads/
  - python https://www.python.org/downloads/


## 安装步骤
- ### 环境配置
1. 显卡程序更新
2. 安装 Git
3. 安装 python，版本要用11以下，目前测试 python-10.0.6 成功
  
- ### 部署 Stable Diffusion
1. 到官网用 git 拉下仓库代码：https://github.com/AUTOMATIC1111/stable-diffusion-webui.git
2. 根据本地系统安装 (下面是贴官方代码)
  
  #### Automatic Installation on Windows
  1. Install [Python 3.10.6](https://www.python.org/downloads/windows/), checking "Add Python to PATH".
  2. Install [git](https://git-scm.com/download/win).
  3. Download the stable-diffusion-webui repository, for example by running `git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git`.
  4. Run `webui-user.bat` from Windows Explorer as normal, non-administrator, user.
 
  #### Automatic Installation on Linux
  1. Install the dependencies:
  ```bash
  # Debian-based:
  sudo apt install wget git python3 python3-venv
  # Red Hat-based:
  sudo dnf install wget git python3
  # Arch-based:
  sudo pacman -S wget git python3
  ```
  2. To install in `/home/$(whoami)/stable-diffusion-webui/`, run:
  ```bash
  bash <(wget -qO- https://raw.githubusercontent.com/AUTOMATIC1111/stable-diffusion-webui/master/webui.sh)
  ```
  3. Run `webui.sh`.

  #### Installation on Apple Silicon
  Find the instructions https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Installation-on-Apple-Silicon

- ### 优化-安装插件
    tag自动提示，中文语言包 等等
