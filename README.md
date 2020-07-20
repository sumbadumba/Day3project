//#include<stdio.h>
//#include<random>
//int main()
//{
//	/*int a = 16;
//	int b = 5;*/
//	//단항연산자
//
//	/*
//	a = 10;
//
//	printf("a = %d\n",a);
//
//	a += 10;
//
//	printf("a = %d\n", a);
//
//	a -= 10;
//
//	printf("a  = %d\n", a);
//
//	a *= 10;
//
//	printf("a  = %d\n", a);
//
//	a /= 10;
//
//	printf("a  = %d\n", a);
//*/
////논리 연산자 && || == != 
////조건문
//
//	//bool condition1 = true;
//	//bool condition2 = false;
//	//bool condition3 = true;
//
//
//	//if (condition1 != !condition2)//두개 다 true 일경우 통과가 된다(1 == false, 2 == false
//	//{//다르냐?
//	//	printf("first condition\n");
//
//	//}//두세트 중 하나의 세트만 ture일 경우 통과한다
//	//else if (!condition1 == condition3)// 1 == false, 2 == true
//	//{
//	//	printf("second condition\n");
//	//}
//	//else
//	//	printf("third condition \n");
//	//if (condition1 || condition2)//두개 중 하나가 true 일경우 통과가 된다
//	//{
//	//	printf("condition is true");
//
//	//}
//	//else
//	//	printf("condition is false");
//
//	/*>,<,<=, >= */
//
//
//	//if ((a%b) == 1)//둘다 1 이여야함
//	//{
//	//	printf("first condition\n");
//
//	//}
//	//printf("program is end");
//
//	//int a = 9;
//	//int b = 9;
//	//int c = 11;
//
//	//if (a >= b)
//	//{
//	//	printf("fornt is big\n");
//	//}
//
//
//	//printf("program is end~ ");
//	//int lotto = 1;
//	//int salary = 4000;
//
//	//printf("hi\n");
//	//if (!((lotto == 1) || salary > 3000))//로또가 1등이거나 월급이 3000이상이면 통과
//	//{
//	//	printf("땅을 사자\n");
//	//}
//	
//	//if (((lotto == 1) || salary > 3000))//로또가 1등이거나 월급이 3000이상이면 통과
//	//{
//	//	printf("땅을 사자\n");
//	//}
//	//else if ((lotto == 2) || salary > 4000)//로또가 1등이거나 월급이 3000이상이면 통과
//	//{
//	//	printf("주식을 사자\n");
//	//}
//	//else if (lotto == 3)
//	//{
//	//	printf("회사 다니자\n");
//
//	//}
//	//else
//	//	printf("공부나 하자");
//
//	//f9을 누르면 브레이크 포인트를 생성한다
//
//
//	/*
//		로또 희망 당첨 등수를 입력받아서
//		각 등수에 맞게 if문 만들고 당첨시 하고싶은거 출력할 수 있게
//		1~5등은 if / else if 로 만들고 1~4qjadnlfmf qjtdjskaus
//		else문으로 들어갈 수 있게
//
//	*/
//
//	
//	/*int lottoRank;
//
//	printf("로또 희망 당첨 등수를 입력 -- > ");
//	scanf("%d", &lottoRank);
//
//	
//	if (lottoRank == 5)
//	{
//		printf("1등입니다.");
//
//	}
//	else if (lottoRank == 4)
//	{
//		printf("2등입니다.");
//
//	}
//	else if (lottoRank == 3)
//	{
//		printf("3등입니다.");
//
//	}
//	else if (lottoRank == 2)
//	{
//		printf("4등입니다.");
//
//	}
//	else if (lottoRank == 1)
//	{
//		printf("5등입니다.");
//	}
//	else
//		printf("순위권 밖입니다.");
//	*/
//	/*국영수 3과목 점수를 입력받아 평균 점수가 
//		60점 이상이면 합격 아니면 불합격
//		1)단, 한 과목의 점수가 40이하면 과락*/
//	
//
//
//
//}
#include<stdio.h>
#include<float.h>

int main()
{
	int math, korean, english;
	float average;
	int down = 40;


	printf("당신의 국어점수는? ");
	scanf("%d", &korean);
	printf("당신의 수학점수는? ");
	scanf("%d", &math);
	printf("당신의 영어점수는?");
	scanf("%d", &english);

	if (korean < down || math < down || english < down)//3과목중에서 한과목이라도 과락이 있으면 
	{
		printf("3과목중 과락한 과목이 있습니다. \n");
	}

	else
	{
		average = (math + korean + english) / 3;

		printf("\n\n당신의 3과목 평균 점수는 %2.f입니다.", average);
	}

	//프로그래머는 솔루션을 제공하는 것이다.
	
	/*숙제 -- > 가진 돈 수치로 코인 환산해서 출력 만들기
		가진 조개 껍데기 2,864,953,217개
		1동화  100껍대기 
		1 은화 = 200동화
		1 금화 = 120 은화
		1 루비 = 80 루비*/


}
