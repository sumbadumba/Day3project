#include<stdio.h>
#include<random>
int main()
{
	/*int a = 16;
	int b = 5;*/
	//단항연산자

	/*
	a = 10;

	printf("a = %d\n",a);

	a += 10;

	printf("a = %d\n", a);

	a -= 10;

	printf("a  = %d\n", a);

	a *= 10;

	printf("a  = %d\n", a);

	a /= 10;

	printf("a  = %d\n", a);
*/
//논리 연산자 && || == != 
//조건문

	//bool condition1 = true;
	//bool condition2 = false;
	//bool condition3 = true;


	//if (condition1 != !condition2)//두개 다 true 일경우 통과가 된다(1 == false, 2 == false
	//{//다르냐?
	//	printf("first condition\n");

	//}//두세트 중 하나의 세트만 ture일 경우 통과한다
	//else if (!condition1 == condition3)// 1 == false, 2 == true
	//{
	//	printf("second condition\n");
	//}
	//else
	//	printf("third condition \n");
	//if (condition1 || condition2)//두개 중 하나가 true 일경우 통과가 된다
	//{
	//	printf("condition is true");

	//}
	//else
	//	printf("condition is false");

	/*>,<,<=, >= */


	//if ((a%b) == 1)//둘다 1 이여야함
	//{
	//	printf("first condition\n");

	//}
	//printf("program is end");

	//int a = 9;
	//int b = 9;
	//int c = 11;

	//if (a >= b)
	//{
	//	printf("fornt is big\n");
	//}


	//printf("program is end~ ");
	//int lotto = 1;
	//int salary = 4000;

	//printf("hi\n");
	//if (!((lotto == 1) || salary > 3000))//로또가 1등이거나 월급이 3000이상이면 통과
	//{
	//	printf("땅을 사자\n");
	//}
	
	//if (((lotto == 1) || salary > 3000))//로또가 1등이거나 월급이 3000이상이면 통과
	//{
	//	printf("땅을 사자\n");
	//}
	//else if ((lotto == 2) || salary > 4000)//로또가 1등이거나 월급이 3000이상이면 통과
	//{
	//	printf("주식을 사자\n");
	//}
	//else if (lotto == 3)
	//{
	//	printf("회사 다니자\n");

	//}
	//else
	//	printf("공부나 하자");

	//f9을 누르면 브레이크 포인트를 생성한다


	/*
		로또 희망 당첨 숫자를 입력받아서
		각 등수에 맞게 if문 만들고 당첨시 하고싶은거 출력할 수 있게
		1~5등은 if / else if 로 만들고 1~4qjadnlfmf qjtdjskaus
		else문으로 들어갈 수 있게
	*/

	
	int lottoRank;

	printf("로또 희망 당첨 숫자를 입력 -- > ");
	scanf("%d", &lottoRank);

	
	if (lottoRank == 5)
	{
		printf("1등입니다.");

	}
	else if (lottoRank == 4)
	{
		printf("2등입니다.");

	}
	else if (lottoRank == 3)
	{
		printf("3등입니다.");

	}
	else if (lottoRank == 2)
	{
		printf("4등입니다.");

	}
	else if (lottoRank == 1)
	{
		printf("5등입니다.");
	}
	else
		printf("순위권 밖입니다.");
}
