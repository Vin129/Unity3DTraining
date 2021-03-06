## 外观模式  
### 简介  
在现实的项目当中，总会有一些遗留的难以维护的大型项目存在，但是这些存在的系统却能在某些场合发挥重要的作用，所以后续的开发人员不希望这种系统被废弃掉，一些新的开发需求就会依赖与这些难以维护的系统，在这种情况下，使用外观模式就可以很好滴解决各种各样可能发生的问题。  
### 定义  
为子系统中的一组接口提供一个一致的界面，此模式定义了一个高层的接口，这个接口使得这一子系统更加容易使用。事实上外观模式的主体只有Facede这一个类而已。 
### Tips  
外观模式使用的最佳时期就是像开头所说的那样，在需要复用一个庞大而又难以维护的旧系统的时候，但是并不是说只有在这一种情况下才能使用到外观模式。就算是在设计的初期，也可以通过外观模式将数据层，业务层进行链接。同样的，当子系统的设计演变的越来越复杂的时候，外观模式也可以就此提供一个简单的接口来减少各个日益复杂的子系统时间的依赖。  
### 小结  
面向对象的程序设计可以避免将程序设计为一个单一的个体，这样一来也就避免了将程序的所有部分都混在在一起会导致的问题。最理想的面向对象应用程序就是一个最小的类，这个类能有把其他可以复用的类的行为进行有效的组织。  
外观模式适用于以下几种情况：  
* 当需要为一个复杂的子系统提供一个简单的接口时；  
* 当客户端与抽象类的实现部分之间存在很大的依赖性时；  
* 当需要构建一个层次结构的子系统时。



