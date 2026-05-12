# EX01
```
import gradio as gr def greet(name): 	return "你好: " + name + "!" 	app = gr.Interface(fn=greet, 					inputs="text", 			outputs="text") 
app.launch()
```


# Software installation
## Download Miniconda

```
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```

## Install Miniconda
```
bash Miniconda3-latest-Linux-x86_64.sh
```

## Setting Path for Miniconda

```
vi ~/.bashrc
```

add the following content into .bashrc file.

```
export PATH="$HOME/miniconda3/bin:$PATH"
```

## Validate the installation
```
conda --version
```
