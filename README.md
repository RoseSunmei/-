# -public class sizeyunsuan{
	public static void main(String[]args){
		for (int i=0;i<30;i++){
	
		int num1 = (int)(Math.random() * 100 +0);
		int num2 = (int)(Math.random() * 100+0 );
		int num3 = (int)(Math.random() * 100+0 );
		int num4 = (int)(Math.random() * 100+0 );	
		
		
		
		int n=num1%4;
		switch(n){
		
		
		case 0:
			if(num1%num2==0&&num3%num4==0){
			System.out.println(num1/num2+"+"+num3/num4+"=");
			}
			if(num1%num2==0&&num3%num4!=0){
				System.out.println(num1/num2+"+"+num3+"/"+num4+"=");}
			if(num1%num2!=0&&num3%num4==0){
				System.out.println(num1+"/"+num2+"+"+num3/num4+"=");}
			if(num1%num2!=0&&num3%num4!=0){
				System.out.println(num1+"/"+num2+"+"+num3+"/"+num4+"=");}
		case 1:
			if(num1%num2==0&&num3%num4==0){
				System.out.println(num1/num2+"-"+num3/num4+"=");}
				if(num1%num2==0&&num3%num4!=0){
					System.out.println(num1/num2+"-"+num3+"/"+num4+"=");}
				if(num1%num2!=0&&num3%num4==0){
					System.out.println(num1+"/"+num2+"-"+num3/num4+"=");}
				if(num1%num2!=0&&num3%num4!=0){
					System.out.println(num1+"/"+num2+"-"+num3+"/"+num4+"=");}
		case 2:
			if(num1%num2==0&&num3%num4==0){
				System.out.println(num1/num2+"*"+num3/num4+"=");}
				if(num1%num2==0&&num3%num4!=0){
					System.out.println(num1/num2+"*"+num3+"/"+num4+"=");}
				if(num1%num2!=0&&num3%num4==0){
					System.out.println(num1+"/"+num2+"*"+num3/num4+"=");}
				if(num1%num2!=0&&num3%num4!=0){
					System.out.println(num1+"/"+num2+"*"+num3+"/"+num4+"=");}
		case 3:
			if(num1%num2==0&&num3%num4==0){
				System.out.println(num1/num2+"/"+num3/num4+"=");}
				if(num1%num2==0&&num3%num4!=0){
					System.out.println(num1/num2+"/"+num3+"/"+num4+"=");}
				if(num1%num2!=0&&num3%num4==0){
					System.out.println(num1+"/"+num2+"/"+num3/num4+"=");}
				if(num1%num2!=0&&num3%num4!=0){
					System.out.println(num1+"/"+num2+"/"+num3+"/"+num4+"=");}
				}
		}
		}
	}

	

