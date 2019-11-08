[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-shadow4android-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/1188)

shadow4android
==============

*Android 9-patch shadow generator*

#### Examples
![](/examples/fill.png?raw=true "Shadow with Fill")
![](/examples/transparent.png?raw=true "Shadow")



#### explain

这次项目遇到老板要求阴影效果，美工离职，又碰上屏幕适配和shadowLayout阴影框架冲突，网上各种方法试遍了效果都不理想，后来发现的好东西，还是自己动手丰衣足食。

Android在5.0中提出了“高度”的概念，并提供了elevation属性给开发者直接设定z值高度。但其效果与Axure设计图相差甚远：
![](/examples/1.webp?raw=true "Shadow with Fill")

## 对比Axure的阴影属性和该网站支持的属
![](/example/2.webp?raw=true "Shadow with Fill")
![](/example/3.webp?raw=true "Shadow with Fill")
从上表可知，使用点九图制作，理论上可以完美实现和Axure设计图一致的阴影效果。

#### 注意事项

## 需要根据屏幕像素等级制作不同分辨率的点九图

虽然Android设备可以根据自身屏幕像素等级对资源进行缩放，但很多人都有切图的需求。针对不同分辨率需要制作的点九图是不同的，这里举例说明一下：
![](/example/4.webp "Shadow with Fill")

Layout XML files: 

* [filled rect with shadow for content panels etc.](/examples/shadow_fill.xml?raw=true)
* [transparent shadow for photos, textures  etc.](/examples/shadow_transparent.xml?raw=true)

> [Youtube  example](https://www.youtube.com/watch?v=ZOK6gEH8qIU)

### License
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
    http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
