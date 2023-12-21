#include <bits/stdc++.h>
#define penguin ios::sync_with_stdio(0); cin.tie(0);
using namespace std;
	
typedef long long ll;
	
int main(void) {
	penguin
	int k;
	cin >> k;
	int highest = INT_MIN, T = 0;
	int fail = 0;
	for(int i = 0; i < k; i++) {
		int t, s;
		cin >> t >> s;
		if(s == -1) {
			fail++;
		}
		else if (s > highest) {
				highest = s;
				T = t;
		}
	}
	cout << max(highest - k - fail * 2, 0) << " " << T << "\n";
	return 0;
}
