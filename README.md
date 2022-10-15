### Algorithm-Visualizer-Using-pygame
# Pygame
Pygame is a set of Python modules designed for writing video games. Pygame adds functionality on top of the excellent SDL library. This allows you to create fully featured games and multimedia programs in the python language.

Pygame is highly portable and runs on nearly every platform and operating system.

Pygame itself has been downloaded millions of times.

Pygame is free. Released under the LGPL licence, you can create open source, freeware, shareware, and commercial games with it. See the licence for full details.

For a nice introduction to pygame, examine the line-by-line chimp tutorial, and the introduction for python programmers. buffer, and many other different backends... including an ASCII art backend! OpenGL is often broken on linux systems, and also on windows systems - which is why professional games use multiple backends.

Multi core CPUs can be used easily. With dual core CPUs common, and 8 core CPUs cheaply available on desktop systems, making use of multi core CPUs allows you to do more in your game. Selected pygame functions release the dreaded python GIL, which is something you can do from C code.

# About Project 
By using the pygame library we will visualize all the sorting algorithm. By looking at the graph how data is sorted we will analyze which sorting technique perform best under a specificc situatiion. 
Following Algorithms will be covered here 
# https://youtu.be/0J7Sf7brv60
## Bubble sort 
Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in the wrong order. This algorithm is not suitable for large data sets as its average and worst-case time complexity is quite high.
## selection sort

## insertion sort 

## Merge Sort

##Quicksort
QuickSort is a Divide and Conquer algorithm. It picks an element as a pivot and partitions the given array around the picked pivot. There are many different versions of quickSort that pick pivot in different ways. 
Always pick the first element as a pivot.
Always pick the last element as a pivot (implemented below)
Pick a random element as a pivot.
Pick median as the pivot.
The key process in quickSort is a partition(). The target of partitions is, given an array and an element x of an array as the pivot, put x at its correct position in a sorted array and put all smaller elements (smaller than x) before x, and put all greater elements (greater than x) after x. All this should be done in linear time.
## Bucket Sort 
## Cocktail Sort
