���������
���£�
	1.git ʹ�ó���  github ������
	2.����������
		�ࣺ
		��ͨ�������ࣻ����һ����
		�������ഴ��һ������
		����һ�������
		��




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