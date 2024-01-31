
# LLAMA V1

## Windows环境部署

 准备独立的python环境
```bash
> cmd
> cd D:\devtools\PythonVenv
> python3 -m venv llama.v1
> D:\devtools\PythonVenv\llama.v1\Scripts\activate.bat
> set http_proxy=192.168.2.199:58591
> set http_proxy=192.168.2.199:58591
```

部署推理环境

```bash
> pip install -r requirements.txt
> pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```

python环境切换
```bash
> cmd
> D:\devtools\PythonVenv\llama.v1\Scripts\activate.bat
```



> export http_proxy=192.168.2.199:58591
> exportt http_proxy=192.168.2.199:58591