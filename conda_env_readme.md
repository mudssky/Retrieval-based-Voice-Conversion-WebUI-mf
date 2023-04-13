## 开发环境安装



从导出的conda env 配置文件创建虚拟环境

```shell
conda env create --name rvc --file=conda_env.yaml
```

pytorch需要单独安装，

如果是没有cuda的，安装cpu版本

```
pip install torch  torchaudio
```

有cuda，就安装cuda版本

```
pip3 install torch  torchaudio --index-url https://download.pytorch.org/whl/cu118
```





## 导出虚拟环境

导出现在的conda_env

```shell
conda env export > .\conda_env.yaml
```

导出到cpu版本，和cuda版本的环境

```'
conda env export > .\conda_env_cpu.yaml
```

```
conda env export > .\conda_env_cuda.yaml
```



