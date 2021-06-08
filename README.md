# Lymphoblast-Project

1. Open GCP in a Google tab.
![1](https://user-images.githubusercontent.com/54854638/121185224-09c9d480-c890-11eb-87f2-244cbea86e24.PNG)
2. Log in to GCP using gmail account.
![2](https://user-images.githubusercontent.com/54854638/121185350-2b2ac080-c890-11eb-80a7-3339fad76c2d.PNG)
3. Claim GCP Voucher to get free billing credit.
![3](https://user-images.githubusercontent.com/54854638/121185632-76dd6a00-c890-11eb-9a36-d2e6a5cdbf65.PNG)
4. Make a new project.
![4](https://user-images.githubusercontent.com/54854638/121185753-98d6ec80-c890-11eb-84d5-ab1f9809211d.PNG)
5. Linked the project to billing account.
![5](https://user-images.githubusercontent.com/54854638/121186022-dc315b00-c890-11eb-9bbb-6a0c7b55c167.PNG)
6. Go to IAM & Admin menu, add member and specify its specific role, then save.
![6](https://user-images.githubusercontent.com/54854638/121186110-ef442b00-c890-11eb-895e-05147452d177.PNG)
7. Go to Compute Engine > VM Instances.
![image](https://user-images.githubusercontent.com/54854638/121186284-21558d00-c891-11eb-934b-a8d5389410a0.png)
8. Create VM instance with configurations as needed, authors use Machine Family General-Purpose Series N1 and Boot Disk Ubuntu-18.04.
![8](https://user-images.githubusercontent.com/54854638/121186684-8dd08c00-c891-11eb-8e17-27ea7bd6ad7a.PNG)
9. Open Firebase in a Google tab.
![9](https://user-images.githubusercontent.com/54854638/121186844-af317800-c891-11eb-8282-4b18b6b97573.PNG)
10. Add project, then click create a project.
![10](https://user-images.githubusercontent.com/54854638/121186965-c5d7cf00-c891-11eb-840e-6eefa196fd7a.PNG)
11. For project name, connect your GCP Project by choose it on Firebase Project.
![11](https://user-images.githubusercontent.com/54854638/121187149-f3bd1380-c891-11eb-9719-4bbb4943834a.PNG)
12. Choose your plan (Blaze), then continue.
13. In Firebase, deploy your Android model to Firebase.
![12](https://user-images.githubusercontent.com/54854638/121187301-2109c180-c892-11eb-9199-99772f1f3354.PNG)
14. Create bucket for upload lymphoblast images from users.
![13](https://user-images.githubusercontent.com/54854638/121187702-8c539380-c892-11eb-94a9-77adc746440d.PNG)
15. Users will upload images via Android interface, then they will be automatically uploaded to Firebase storage.
![14](https://user-images.githubusercontent.com/54854638/121188178-0dab2600-c893-11eb-86a7-8c9fce269f8a.PNG)
16. Move to GCP again.
![15](https://user-images.githubusercontent.com/54854638/121188242-1f8cc900-c893-11eb-9905-423b410d2f48.PNG)
17. Go to Cloud Storage > Browser.
![16](https://user-images.githubusercontent.com/54854638/121188469-56fb7580-c893-11eb-8c96-2f67da9f54a5.PNG)
![17](https://user-images.githubusercontent.com/54854638/121188509-611d7400-c893-11eb-8483-c5ecb84bfd51.PNG)
18. As you can see, the images also can be seen and edited on GCP bucket cloud storage.
![18](https://user-images.githubusercontent.com/54854638/121188531-68448200-c893-11eb-92c1-de7fc3f21bd5.PNG)
19. To make the images and bucket become public, choose the bucket and click the three dots, then choose edit bucket permissions.
![17](https://user-images.githubusercontent.com/54854638/121188509-611d7400-c893-11eb-8483-c5ecb84bfd51.PNG)
![19](https://user-images.githubusercontent.com/54854638/121188889-bd809380-c893-11eb-8ce4-e4ed6201d709.PNG)
20. Click add member.
![20](https://user-images.githubusercontent.com/54854638/121188971-d38e5400-c893-11eb-83b6-9d2691a50a95.PNG)
21. On new member, type "allUsers".
![21](https://user-images.githubusercontent.com/54854638/121189086-f4ef4000-c893-11eb-8fad-88fdfbd3f669.PNG)
22. On select a role, specify the roles to Cloud Storage > Storage Object Viewer.
![21](https://user-images.githubusercontent.com/54854638/121189108-f882c700-c893-11eb-9403-a399d3259809.PNG)
23. Files in buckets are publicly accessible.
![15](https://user-images.githubusercontent.com/54854638/121187592-6af2a780-c892-11eb-81fa-f051d341b8e1.PNG)

