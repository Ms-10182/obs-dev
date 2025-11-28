

## 🎯 Goal
Become confident in core DSA patterns and crack placement-level questions by **9 August**

---

## ✅ Progress Tracker
[[Problem tracker]]

	Date -  26/7/25
Topic : selection sorting
```
void selectionSort(vector<int> & arr){

    for(int i=0;i<arr.size()-1;i++){

        int minIdx = i;

        for(int j =i+1;j<arr.size();j++){

            if(arr[minIdx]>arr[j]){

                minIdx=j;

            }

        }

        swap(arr[minIdx],arr[i]);

    }

}
```

Topic : bubble sorting 
```void bubbleSort(vector<int> &arr){

    for (int i = 0; i < arr.size(); i++){

        for (int j = 0; j < arr.size() - 1 - i; j++){

            if (arr[j] > arr[j + 1])

            {

                swap(arr[j], arr[j + 1]);

            }

        }

        for (auto a : arr)

        {

            cout << a << " ";

        }

        cout<<endl;

    }

}
```
