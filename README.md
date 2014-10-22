今天的内容
如下：
	1.git 使用初步  github 的配置
	2.面向对象初步
		类：
		交通工具是类；车是一个类
		可以用类创建一个对象
		类是一个概念集合
		耦




class Person{
	private int age;

	eat();
	getAge();
	setAge(int age){
		this.age = age;
		age+=1;
	};

	public static Person getInsance(skinColor color){
		switch(color){
			case YELLOW:
				return new YellowPerson();
			case WHITE:
				return new WhitePerson();
			case
			default:
				throw COLORError();
		}
	}

	enum skinColor{
		YELLOW,BLACK,WHITE
	}
}
class Factory{}
Bitmap

class YellowPerson{
	public YellowPerson(int age,float height,float weight, ){
	}
}

class BlackPerson{
	
}



class ImageLoader{
	ImageLoader loaderSelf= null
	getInstance(){
		if(loaderSelf == null)
			return loaderSelf = new loaderSelf();
		else 
			return loaderSelf;	
	}
}

class Test{
	public static final main(String[] args){
		Person person = getInstance(skinColor.YELLOW);
		ImageLoader.getInstance()......;
	}
}