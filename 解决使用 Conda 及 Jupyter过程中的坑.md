### Mac下解决使用 Conda 及 Jupyter过程中的坑



**1. conda or Jupyter command not found**

``` $ export PATH=~/anaconda3/bin:$PATH```



**2. 为了让 conda 和 jupyter 命令默认,可以执行以下步骤:**

- ```$ vim ~/.bash_profile```

- a

- export PATH="~/anaconda3/bin:$PATH"

- esc

- :wq

- 关闭 terminal

- 重新打开 terminal 即可以使用

  

**3. 使用 conda 管理虚拟环境**

- 创建虚拟环境 :      ```$ conda create --name 新环境```

- 克隆虚拟环境:       ```$ conda create --name 新环境 --clone base```

- 激活虚拟环境:       ```$ conda activate 新环境```

- 关闭虚拟环境:       ```$ conda deactivate 新环境```



**4. 使用 conda 管理包**

- ```$ conda install nltk``` (安装package)
- ``` $ conda install gensim``` (安装package)
- ```$ conda uninstall nltk``` (卸载package)



**5. 使用 Jupyter notebook 时切换虚拟环境**

- 激活新环境:      ``` $ conda activate 新环境 ```

- 安装 nb_conda 包:      ```$ conda install nb_conda ```  
- 安装 ipykernel :      ``` $ conda install ipykernel```
- 手动配置(kernel):     ``` $ python -m I-kernel install --user --name 新环境 --display-name "Python (新环境) "```
- 执行完上述步骤:  即可执行 ``` $ jupyter notebook``` 打开 notebook, 在 Kernel 选项下即可切换 虚拟环境



















