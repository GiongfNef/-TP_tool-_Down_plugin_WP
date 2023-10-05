# TP Tool: WordPress Plugin Downloader

TP Tool is a Python script that allows you to easily download and extract WordPress plugins from their respective URLs. This tool simplifies the process of obtaining plugins for your WordPress website.

## Prerequisites

Before using TP Tool, make sure you have the following:

- Python 3 installed on your system
- Internet connectivity to download the plugin from the provided URL

## Installation

To use TP Tool, you can clone the repository from GitHub. Follow the steps below:

1. Open your terminal or command prompt.
2. Navigate to the directory where you want to clone the repository.
3. Run the following command:
```bash
git clone https://github.com/GiongfNef/-TP_tool-_Down_plugin_WP.git
```
4. Once the repository is cloned, navigate to the cloned directory:
```bash
cd -TP_tool-_Down_plugin_WP
```

## Usage

To run TP Tool and download a WordPress plugin, use the following command:
```python
python TP_download_plugin.py -u <URL> -o <OUTPUT>
```
Replace `<URL>` with the URL of the plugin you want to download and `<OUTPUT>` with the output path where you want to store the downloaded plugin.

### Example

Here's an example command that demonstrates how to use TP Tool:
```python
python TP_download_plugin.py -u https://wordpress.org/plugins/yatra/ -o C:\Downloads
```

This command will download the Yatra WordPress plugin from the provided URL and store it in the `C:\Downloads` directory.

## Options

TP Tool supports the following options:

- `-h, --help`: Show the help message and exit.
- `-u URL, --url URL`: Specify the URL of the plugin to download.
- `-o OUTPUT, --output OUTPUT`: Specify the output path to store the downloaded plugin.

## Support

If you encounter any issues or have questions about TP Tool, please feel free to reach out to the developer at giongfnef26@intigriti.me



"# -TP_tool-_Down_plugin_WP" 

