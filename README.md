# Java Square Factory

**Create rectangles with (x,y) points and display to console.**

Each element represents coordinates for points in the form (x,y). Rectangles built with odd element point pairs represent top-left points, while even elements represent bottom-right points.

    double[][] coords = {
        // rectangle #1
        {1.0 , 1.0},        // element 0 : point #1, bottom-left
        {1.0 , 3.0},        // element 1 : point #2, top-left
        {4.0 , 3.0},        // element 2 : point #3, top-right
        {4.0 , 1.0},        // element 3 : point #4, bottom-right
    ...
    };