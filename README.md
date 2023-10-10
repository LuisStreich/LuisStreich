- 👋 Hi, I’m @LuisStreich
- 👀 I’m interested in programation
- 🌱 I’m currently learning ADS
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me luisstreich2005@gmail.com
#include<stdio.h>
main(){
	double peso, altura,IMC;
	puts("digite o peso");
	scanf("%lf",& peso);
	puts("digite altura");
	scanf("%lf",& altura);
	IMC=peso/(altura*altura);
	if (IMC < 18.5){
		printf("abaixo do peso");
	}else if (IMC >= 18 && IMC < 25){
		printf("peso normal");
	}else if (IMC >= 25 && IMC < 30){
		printf("sobrepeso");
	}else if (IMC >= 30 && IMC < 35){
		printf("obesidade grau 1");
	}else if(IMC >= 35 && IMC < 40){
		printf("obesidade grau 2");
	}else if (IMC > 40)
		printf("obesidade grau 3");	
}
