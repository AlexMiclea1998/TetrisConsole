# TetrisConsole

Console Tetris, one class.

#Controls
Arrows Left, Right and Down.
'Z' to rotate the pieces the more lines u break at once the more points you earn.

Shapes are drawn using wstring in C++ eg. 
    
    wstring tetromino[7];
    tetromino[0].append(L"..X.");
    tetromino[0].append(L"..X.");
    tetromino[0].append(L"..X.");
    tetromino[0].append(L"..X.");
    
    The 'Xs' represent the line in a 4x4 matrix.
    
Gameplay:    
![image](https://user-images.githubusercontent.com/50875057/113515806-5981dc00-957f-11eb-9eed-6c58dc2c85dd.png)

After 50 blocks, the speed increases.

![image](https://user-images.githubusercontent.com/50875057/113515840-8a621100-957f-11eb-84ce-53e2aec61639.png)

If you reach the top and another piece can't be drawn the game will finish and you will lose.

![image](https://user-images.githubusercontent.com/50875057/113515828-71f1f680-957f-11eb-98a4-fe31a06f6800.png)
