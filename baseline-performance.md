![Screenshot 2022-11-06 224428](https://user-images.githubusercontent.com/98288056/200226232-452ea833-57be-464a-8d84-df70e96e2001.png)
![Screenshot 2022-11-06 224512](https://user-images.githubusercontent.com/98288056/200226238-675254fa-550c-4a0a-bdf9-50994a511306.png)
![Screenshot 2022-11-06 224639](https://user-images.githubusercontent.com/98288056/200226241-b43aed18-2332-4316-973e-f13be8476205.png)
![Screenshot 2022-11-06 224753](https://user-images.githubusercontent.com/98288056/200226243-da04b1e8-25a6-43f2-aa84-4c0a9c8df1a7.png)
![Screenshot 2022-11-06 224753](https://user-images.githubusercontent.com/98288056/200226245-cef7ec2d-d341-442c-948e-60d009acd849.png)
![Screenshot 2022-11-06 224823](https://user-images.githubusercontent.com/98288056/200226248-b6c0a3db-7a5d-4c79-bd3e-9f9b17878570.png)
![Screenshot 2022-11-06 224928](https://user-images.githubusercontent.com/98288056/200226249-e1b34eef-3b46-4715-bef8-299d00e80143.png)
![Screenshot 2022-11-06 225009](https://user-images.githubusercontent.com/98288056/200226254-d7ee6188-dfeb-45f5-ab6e-a91a83f086ea.png)
![Screenshot 2022-11-06 225034](https://user-images.githubusercontent.com/98288056/200226259-a1591e8d-d416-4b74-85d8-fb839660b40b.png)
![Screenshot 2022-11-06 225107](https://user-images.githubusercontent.com/98288056/200226264-f50c7f13-d577-412e-ab66-af9e326339c1.png)
![Screenshot 2022-11-06 225215](https://user-images.githubusercontent.com/98288056/200226271-46a89dae-2548-44ed-aee3-7037e2e7288b.png)
![Screenshot 2022-11-06 225251](https://user-images.githubusercontent.com/98288056/200226339-9d87b130-711e-477b-b99f-6727f10dfe72.png)
![Screenshot 2022-11-06 225356](https://user-images.githubusercontent.com/98288056/200226350-c97c2785-db04-497a-a397-c12205d17374.png)
![Screenshot 2022-11-06 232700](https://user-images.githubusercontent.com/98288056/200226552-85a5a256-25e7-4a9f-8ee1-88158b4e2c4d.png)
Where it was good. Then from the other file simple_multi_unet_model we imported the multi_unetmodel and jacard coef where the image model was made 
with height width channels and then was compiled in optimizer ‘adam’ where is all the patches of images were checked and given, they are all multiples 
256 since our patch size was 256. Then the model was loaded in history1 and then did model fir with batch size of 16 and epochs of 100. Where I received 
the accuracy of 61.62 percent. Then tested for training and validation loss. Although not required but also plotted the Graph for IOU And finally I get 
these results which were working well. Then, since our patch size was 256, we imported the multi unetmodel and jacard coef from another file called simple 
multi unet model. This image model was created with height and width channels, and it was then assembled in the optimizer "Adam." All of the image patches 
were then checked and given, and they are all multiples of 256 as a result. The model was then loaded into history1, and model fir was performed with a batch 
size of 16 and 100 epochs. I was given an accuracy score of 61.62 percent there. Then training and validation loss was assessed. Although it wasn't necessary, 
the graph for IOU was also plotted. Finally, I receive these outcomes.
