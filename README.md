java第二次实验
#阅读程序
#实验目的了解Java中的类，弄清类之间的联系，掌握构造方法，实现定义属性的修饰符近似＃
#实验过程对照书上的UML用例图理清类的关系，了解对象属性
#核心方法主类`公共类测试{公共静态void main（字符串[] args）CPU cpu = new CPU（）; 硬盘HD =新的HardDisk（）; cpu.setSpeed（2200）; HD.setAmount（200）; PC pc =新PC（）; pc.setCPU（cpu）; pc.setHardDisk（HD）; pc.show（）;
}

Test(){
 
}
}CPU公共类CPU {公共类CPU {private int speed; 公共int价格；int getSpeed（）{返回速度；} public void setSpeed（int speed）{this.speed = speed; }
int getPrice(){
 return price;
}
public void setPrice(int price){
 this.price = price;
}
CPU(){
 
}
}} public void setSpeed（int speed）{this.speed = speed; } 中央处理器（）{
}
} PC公共类PC {CPU cpu; 硬盘高清；void setCPU（CPU cpu）{this.cpu = cpu; } void setHardDisk（HardDisk HD）{this.HD = HD; } void show（）{System.out.println（“ cpu速度：” + cpu.getSpeed（））; System.out.println（“硬盘容量：” + HD.getAmount（））;
} PC（）{
}
}HardDisk公共类HardDisk {公共类HardDisk {private int amout; 公共int大小；int getAmount（）{返回amout; } public void setAmount（int amout）{this.amout = amout; }
int getSize(){
 return size;
}
public void setSize(int size){
 this.size = size;
}

HardDisk(){
 
}
} int getAmount（）{返回amout; } public void setAmount（int amout）{this.amout = amout; } 硬盘（）{
}
}
#实验结果
cpu速度：2200硬盘容量：200 

#实验感想了解如何定义对象调用对象，了解了私有的用法，把实验的不同类放在多个包中
