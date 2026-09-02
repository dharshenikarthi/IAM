# EX - 6 Implementation Of Identity Management (Amazon IAM) For Your Team

## NAME: DHARSHENI K
## REG. NO: 212224040073
---

## Aim

To implement identity and access management (IAM) in AWS to securely control access to resources by creating and managing IAM users, groups, roles, and policies for team collaboration.

---

## Algorithm

1. Sign in to the AWS Management Console.
2. Navigate to the IAM service.
3. Create IAM groups with defined policies (e.g., Admin, Developer).
4. Create IAM users and assign them to appropriate groups.
5. Create IAM roles if cross-account or service-based access is needed.
6. Attach permissions using managed or custom policies.
7. Enable MFA (Multi-Factor Authentication) for users.
8. Monitor access using IAM Access Analyzer and CloudTrail.

---

## Procedure

### 1. Access IAM

- Go to *AWS Console* → *Services* → *IAM*.

### 2. Create IAM Groups

- Click *Groups* → *Create New Group*.
- Name the group (e.g., Admins, Developers).
- Attach predefined or custom policies (e.g., AmazonEC2FullAccess).

### 3. Create IAM Users

- Click *Users* → *Add Users*.
- Enter usernames and choose *Programmatic access* and/or *AWS Management Console access*.
- Assign users to the appropriate group.

### 4. Create IAM Roles (if needed)

- Go to *Roles* → *Create Role*.
- Select use case (AWS service, another AWS account).
- Attach necessary permissions.

### 5. Apply Policies

- Use AWS managed policies or create custom JSON-based policies.
- Assign them to users, groups, or roles.

### 6. Enable MFA

- For each user, go to *Security credentials*.
- Click *Manage MFA* → Choose *Virtual MFA device* (e.g., Google Authenticator).

### 7. Monitor IAM Usage

- Use *IAM Access Analyzer* to detect unused permissions.
- Use *CloudTrail* for auditing user activity.

---

### Outcome

## 1.IAM Group Creation

<img width="1917" height="1020" alt="image" src="https://github.com/user-attachments/assets/a7ef8be5-bdd3-48d0-81d5-f250ae922f35" />



## 2.Attach an IAM Policy to the group

<img width="1915" height="1077" alt="image" src="https://github.com/user-attachments/assets/7944dc84-1d34-428f-8c09-1b2b4bd0ec76" />


## 3.Create an IAM User

<img width="1917" height="1082" alt="image" src="https://github.com/user-attachments/assets/e8505df8-154d-4d6c-9f71-c5986f0e7f21" />



## 4.Add The user to the IAM Group

<img width="1917" height="1082" alt="image" src="https://github.com/user-attachments/assets/4edbd93c-f6d6-493d-beb0-6e528dab1604" />



## 5.Verify user Permissions

<img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/a675233b-6fab-47c0-b71f-afd3777a3159" />


<img width="1916" height="1135" alt="image" src="https://github.com/user-attachments/assets/557d3782-4fca-4437-a781-bdf8675d0eab" />



## 6.Verify Least-Privilege Access


<img width="1916" height="1081" alt="image" src="https://github.com/user-attachments/assets/c0733048-e4dc-49be-9e1f-d458f0017173" />

<img width="1917" height="1026" alt="image" src="https://github.com/user-attachments/assets/99561cba-f382-4982-8c75-c05db1ce3555" />





---

## Result

Successfully implemented identity and access management using Amazon IAM for secure team collaboration and controlled access to AWS resources.
