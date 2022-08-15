#define _CRT_SECURE_NO_WARNINGS
#include <iostream>
#include <cstring>
using namespace std;

int main(){
	int N;
	char word[100];
	int i,j;
	int result[100] = { 0, };
	int res = 0, len = 0;

	scanf("%d", &N);
	for (i = 0; i < N; i++) {
		cin >> word;
		for (j = 0; j < strlen(word); j++) {
			result[i] += int(word[j])-96;
		}
		res += result[i];
		len += strlen(word);
	}
	if (res % N == 0 && len % N == 0)
		printf("true");
	else
		printf("false");
}
