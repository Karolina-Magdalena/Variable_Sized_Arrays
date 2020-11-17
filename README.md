# Variable_Sized_Arrays

Dynamic memory allocation

cin>>n;
    int **arr = new int*[n];
    for (int b=0;b<n;b++)
    {
    cin>>k;
    arr[b] = new int[k];
    for (int a=0;a<k;a++)
    {
        cin>>number;
        arr[b][a]=number;
    }
    }


