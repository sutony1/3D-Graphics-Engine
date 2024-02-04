# 3D-Graphics-Engine
OpenGL Graphics Engine in Python ( Pygame, ModernGL ) 

![opengl](/screenshot/0.jpg)
shader_programm.py第一行增加以下：
import os
os.chdir(os.path.dirname(os.path.abspath(__file__)))
vbo.py第一行增加以下
import os
os.chdir(os.path.dirname(os.path.abspath(__file__)))
这句是改加载什么3d图形
objs = pywavefront.Wavefront('objects/cat/GA101.obj', cache=True, parse=True)#objects/cat/20430_Cat_v1_NEW.obj