From the RSNA pneumonea dataset, we find,
1. medical tools/tubes visible
2. some images rotated
3. "L" text given, which means left side of chest
4. both a\p view, p\a view images are present.
 *a\p view , there is enlargement of cardiac shadow. cardiac shadow color is less dark
 * p\a view, there is smaller  cardiac shadow. cardiac shadow color is darker
5. normal, pneumonia image size are similar
6. pixel: 1024*1024
7. images are monocromatic
8.In dicom format

Metadata from a sample dicom image from this dataset:
![rsna dicom image sample metadata](https://user-images.githubusercontent.com/52566550/92305033-2fdee300-efa5-11ea-8c99-a0cd95b63679.png) 

Posterior Anterior vs Anterior Posterior view of dicom images.
![pneumonia pa vs ap](https://user-images.githubusercontent.com/52566550/92305085-a54ab380-efa5-11ea-94fb-4dbfd7b39ed9.png)


From chest x ray dataset, we find,
1. images are of one to five years old children
2.pneumonea images contains both virus and bacteria
3. pneumonea images are low resulation compared to normal
4. in pneumonia x ray images, medical tool/tubes are found  
5. "R" text given, which means right side of chest
6. normal image size bigger.(average 500kb), pneumonia images size are small(100kb average)
7.dimension varries ..all above 700 pixel

from local dataset, we find,
1. lab aid logo
2. chest p\a view text
3.2 images are not chest x ray (LT chest LAT)
4. images are grayscale
5. "R" text given, which means right side of chest
6. 133 images are in p\a view, except 6 a\p x rays (mostly of children).
7.1760*2140 pixels

rsna image and its pixel values :
patient 0 image : 

![rsna patient 0](https://user-images.githubusercontent.com/52566550/92305754-f2ca1f00-efab-11ea-9fb8-661ecb928a92.png)

patient 0 pixel values: 
![rsna patient 0 arrays](https://user-images.githubusercontent.com/52566550/92305767-0ecdc080-efac-11ea-8327-5d8d08be92c1.png)

patient 2 image:
![rsna patient 2](https://user-images.githubusercontent.com/52566550/92305780-29a03500-efac-11ea-9ca8-c5888f60e414.png)

patient 2 array:
![rsna patient 2 array](https://user-images.githubusercontent.com/52566550/92305782-2e64e900-efac-11ea-8cae-dc01128e7c75.png)


Local images and its pixel values:
   patient 3 image:
   ![local patient 3](https://user-images.githubusercontent.com/52566550/92305802-610ee180-efac-11ea-83a8-b32301b7f1b3.png)
   
   patient 3 pixel values:
   ![local patient 3 array](https://user-images.githubusercontent.com/52566550/92305803-6409d200-efac-11ea-940f-a3041c0464ad.png)
   
   
   patient 7 image:
   ![local patient 7](https://user-images.githubusercontent.com/52566550/92305810-6f5cfd80-efac-11ea-9a33-f59761d39f60.png)
   
   patient 7 pixels:
   ![local patient 7 array](https://user-images.githubusercontent.com/52566550/92305815-72f08480-efac-11ea-89b1-3884d2bb9b09.png)
