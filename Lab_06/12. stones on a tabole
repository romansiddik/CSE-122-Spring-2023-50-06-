#include <iostream>
#include <string>

using namespace std;

int main() {

    int n;

    int R = 0 , B = 0 , G = 0;

    char array[55];

    cin >> n;

    for(int i = 0 ; i < n ; i++){

        cin >> array[i];

    }

    if(n <= 50){

        for(int i = 0 ; i < n ; i++){

            if(array[i] == 'R' || array[i] == 'G' || array[i] == 'B'){

                if(array[i] == 'R'){

                    if(array [i] == 'R' && array [i+1] == 'R'){

                        R++;

                    }
                }

                if(array[i] == 'B'){

                    if(array [i] == 'B' && array [i+1] == 'B'){

                        B++;

                    }
                }

                if(array[i] == 'G'){

                    if(array [i] == 'G' && array [i+1] == 'G'){

                        G++;

                    }
                }
            }
        }

        int sum = R + G + B;

        cout << sum << endl;

    } else{

        exit(0);

    }

    return 0;
}
