# Docker for SPIRAL

[Docker](https://docs.docker.com/install/) is easiest way to get the
[SPIRAL](https://github.com/deepmind/spiral) agent up and running on your machine.
There is no need to build anything or install any packages (besides `Docker` itself).

## Quickstart

1. [Install Docker](https://docs.docker.com/install/) on your local host machine.
2. Run the following command in the terminal:

   ```shell
   docker run -it -p 8888:8888 ddtm/spiral:latest
   ```
   
   This will start an instance of [Jupyter Notebook](https://jupyter.org/) server. 
   
   Note that you can replace `8888:8888` with `<HOST_PORT>:8888` where `<HOST_PORT>`
   is a port on your local host machine.
3. Follow the instructions and open the URL in your host web browser: `http://127.0.0.1:8888/?token=...`
4. You should see a file browser. Select `spiral-demo.ipynb`.
5. **Voilà!**

Now you should be able to go through the **demo notebook**. Use `Shift + Enter` to execute a cell
and go to the next one. For more information on how to use Jupyter notebooks see, for example,
[this tutorial](https://www.codecademy.com/articles/how-to-use-jupyter-notebooks).
