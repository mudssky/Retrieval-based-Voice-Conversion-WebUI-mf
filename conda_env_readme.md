从导出的conda env 配置文件创建虚拟环境

```shell
conda env create --name rvc --file=conda_env.yaml
```



导出现在的conda_env

```shell
conda env export > .\conda_env.yaml
```



