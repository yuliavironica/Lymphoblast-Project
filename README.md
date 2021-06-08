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
8. Create VM instance with configurations as needed, authors use Machine Family General-Purpose Series N1 and Boot Disk Ubuntu-1804.

9. Open Firebase in a Google tab.
10. Add project, then click create a project.
11. For project name, connect your GCP Project by choose it on Firebase Project.
12. Choose your plan (Blaze), then continue.
13. In Firebase, deploy your Android model to Firebase.
14. Create bucket for upload lymphoblast images from users.
15. Users will upload images via Android interface, then they will be automatically uploaded to Firebase storage.
16. Move to GCP again.
17. Go to Cloud Storage > Browser.
18. As you can see, the images also can be seen and edited on GCP bucket cloud storage.
19. To make the images and bucket become public, choose the bucket and click the three dots, then choose edit bucket permissions.
20. Click add member.
21. On new member, type "allUsers".
22. On select a role, specify the roles to Cloud Storage > Storage Object Viewer.
23. Files in buckets are publicly accessible.
