# Active-Directory-Home-Lab

Description: This lab shows the details that how to create a AD DS environment with AD DS server and DHCP. It also shows how to create a list of clients for simulation. The client should be connecting to the internet through the default gateway.

![Screenshot 2024-08-22 182001](https://github.com/user-attachments/assets/dfb35141-3c57-4fd1-8b6a-c09200132385)


Creating a AD DS server:

![Screenshot 2024-08-22 131317](https://github.com/user-attachments/assets/9af5a0d2-4943-4e9a-a7b1-61983ba6cff0)

Set up the AD DS administrator:

![Screenshot 2024-08-22 134247](https://github.com/user-attachments/assets/762cccc3-c55e-4a31-b3e2-85def864b722)

Congifure RAS and NAT:

![Screenshot 2024-08-22 141939](https://github.com/user-attachments/assets/b8e05fdd-382e-481a-b13e-8e8d6eae78be)

Set up a DHCP controller on domain server:


![Screenshot 2024-08-22 143311](https://github.com/user-attachments/assets/1abcbe43-17db-433f-b465-3571d8a4cf7d)

Distrubute IP address for clients within a range:



![Screenshot 2024-08-22 145651](https://github.com/user-attachments/assets/13aa9e48-16eb-4e43-a329-8318af70bb7f)
![Screenshot 2024-08-22 145953](https://github.com/user-attachments/assets/08a62dab-74d2-4b37-a1dd-e53c78ab0a11)


It should be like this after setup successfully:

![Screenshot 2024-08-22 150254](https://github.com/user-attachments/assets/246a67fb-ef2c-45c6-86eb-d14f65fa8e3b)


Create a list of users by a script:

![Screenshot 2024-08-22 163644](https://github.com/user-attachments/assets/9f85508e-940f-47e9-8dbc-9719d75d25dd)

Create a client with windows 10:


![Screenshot 2024-08-22 165332](https://github.com/user-attachments/assets/61987850-b995-4e90-a9f4-8cf81bc9438d)


Now CLIENT1 appears in DHCP and AD computers:

![Screenshot 2024-08-22 175430](https://github.com/user-attachments/assets/82804388-6ea5-4d13-ae0e-0c77de959462)

![Screenshot 2024-08-22 175447](https://github.com/user-attachments/assets/985476bd-f1c7-4277-9272-5023a2f2cb35)

CLIENT1 can communicate with outside internet and my domain:

![Screenshot 2024-08-22 181628](https://github.com/user-attachments/assets/a5fce930-8f4a-406c-ae12-3c229a0d8b01)

![Screenshot 2024-08-22 181700](https://github.com/user-attachments/assets/d94a97e6-5285-4c7d-a383-05a2e39db8f3)


