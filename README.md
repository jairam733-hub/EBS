## WORKING WITH EBS

### NAME:JAIRAM J
### REGISTER NO:212225040141
## AIM:

In this lab environment, access to AWS services and service actions might be restricted to the ones that are needed to complete the lab instructions. You might encounter errors if you attempt to access other services or perform actions beyond the ones that are described in this lab.

## OBJECTIVE:
```
*Create an Amazon EBS volume
*Attach and mount your volume to an EC2 instance
*Create a snapshot of your volume
*Create a new volume from your snapshot
*Attach and mount the new volume to your EC2 instance
```
## Illustration:

# STEP 1:
In this step, you will create and attach an Amazon EBS volume to a new Amazon EC2 instance.You will see an existing volume that is being used by the Amazon EC2 instance. This volume has a size of 8 GiB, which makes it easy to distinguish from the volume you will create next, which will be 1 GiB in size.

<img width="1920" height="1200" alt="Screenshot (361)" src="https://github.com/user-attachments/assets/2d38b3fa-e15a-4f89-b157-7938298980fd" />


# STEP 2:
In this step, you will connect to the Lab EC2 instance using Session Manager.You can now attach your new volume to the Amazon EC2 instance.

<img width="948" height="880" alt="image" src="https://github.com/user-attachments/assets/9d246b2f-56e8-4b2b-af35-44a9b343731c" />
<img width="1920" height="1200" alt="Screenshot (363)" src="https://github.com/user-attachments/assets/357fe9b4-7176-4e7d-898d-d78e219518f7" />

# STEP 3:
In this step, you will add the new volume to a Linux instance as an ext3 file system under the /mnt/data-store mount point.

<img width="954" height="878" alt="image" src="https://github.com/user-attachments/assets/d3fab652-842a-435e-b669-1595c636c512" />
<img width="957" height="1078" alt="image" src="https://github.com/user-attachments/assets/095ba2cb-4e7c-44ab-9126-6e8924286359" />
<img width="961" height="1078" alt="image" src="https://github.com/user-attachments/assets/c2f3d615-1745-4d6f-9d0e-1abf4c7179c3" />

# STEP 4:
You can create any number of point-in-time, consistent snapshots from Amazon EBS volumes at any time. Amazon EBS snapshots are stored in Amazon S3 with high durability. New Amazon EBS volumes can be created out of snapshots for cloning or restoring backups. Amazon EBS snapshots can also be easily shared among AWS users or copied over AWS regions.

<img width="954" height="878" alt="image" src="https://github.com/user-attachments/assets/e18a5014-4041-415c-935c-2b48638f30fb" />
<img width="960" height="876" alt="image" src="https://github.com/user-attachments/assets/434dec9a-b3c4-4545-ad56-f8a9d5e9611b" />

# STEP 5:
<img width="1920" height="1080" alt="Screenshot 2026-08-03 162248" src="https://github.com/user-attachments/assets/109bd66c-06c0-4329-b213-0b6f5f47e8dc" />



## RESULT:
Successfully created, managed, and deleted an EBS bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon EBS.

