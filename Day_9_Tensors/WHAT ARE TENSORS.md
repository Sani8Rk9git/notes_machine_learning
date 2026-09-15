**WHAT ARE TENSORS??**



\-> Tensors are data structure.

\-> Tensor is a container to store numbers



\-> Scalar : a single number

\-> Vector : a list of numbers (1D)

\-> Matrix : numbers in rows and columns (a list containing list) (2D)

\-> Tensor : general term for list of numbers in 3D and above



\-> n-D arrays are called tensors



\-> Example of 1-D tensor (vector)

&#x09;-> suppose we have a student dataset of 10,000 students

&#x09;cgpa | iq | state | placement

&#x09;...

&#x09;-> now placement is the output column

&#x09;-> we do the numerical encoding of the state column (represent the state by a 

&#x09;	number)

&#x09;-> the row of a single student \[7.8 , 80 , 3] is a 1-D Tensor (shape: (3,) )

&#x09;-> means each row of the table is 1-D tensor

&#x09;

\-> Example of 2-D tensor (matrix)

&#x09;-> the dataset of the student is a 2-D tensor (matrix) (shape: (row , column) )

&#x09;

\-> Example of 3-D tensor

&#x09;-> it is frequently used in NLP

&#x09;	-> we have given some text and we need to convert text to numbers 

&#x09;		(this is known as vectorization)

&#x09;	-> Hi Ansh                       Hi | Ansh | Ram | Shyam

&#x20;		-> Hi Ram                        1     0      0      0

&#x09;	-> Hi Shyam                      0     1      0      0

&#x20;                                                0     0      1      0

&#x20;                                                0     0      0      1

&#x09;	-> \[ \[ \[1,0,0,0] , \[0,1,0,0] ] , \[] , \[] ]

&#x09;	-> so the sentences are collection of 2-D tensors which is 3-D tensors

&#x09;	-> shape : (3,2,4) 

&#x09;-> Time series data

&#x09;	-> collected after some time period

&#x09;	-> suppose we are storing the highest and lowest price of a stock

&#x09;	-> the shape is (365,2) --> for a year we do this

&#x09;	-> for the 10 years --> (10,365,2) --> 3-D tensor

&#x09;	

\-> Example of 4-D tensors

&#x09;-> image based data

&#x09;-> in the domain of computer vision

&#x09;-> An image is a collection of pixels

&#x09;-> each pixel has RGB channels (red , green , blue) --> each 2-D tensor

&#x09;-> suppose each is a matrix (1200,800)

&#x09;-> the space of 3 is : (3,1200,800) --> a single image

&#x09;-> collection of images : suppose we have 40 images 

&#x09;	-> (40,3,1200,800) --> 4-D tensors



\-> Example of 5-D tensors

&#x09;-> videos

&#x09;	-> these are images that move very fast in one second

&#x09;-> single frame means 1 image 

&#x09;-> suppose we have one video of 60 seconds shoot at 30 fps (frames per second)

&#x09;	-> 1 sec = 30 images

&#x09;	-> 60 sec = 1,800 images

&#x09;	-> (1800,3,480,720)

&#x09;-> suppose we have 10 such videos

&#x09;	-> (10,1800,3,480,720) --> 5-D tensors

&#x09;	-> since this can take large storage, so we use video encoding

&#x09;		(mkv, mpeg , mp4)

&#x09;

&#x09;

&#x09;

&#x09;





