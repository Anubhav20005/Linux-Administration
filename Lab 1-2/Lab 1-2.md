<h1>
    🚀  LAB 1 - 2 🚀
</h1>

<h3>
    1. Create the operator1 user and confirm that it exists in the system. Set the password for operator1. Create the additional operator2 and operator3 users. Set their passwords as well.
    <br><br>
    2. Run the usermod -c command to update the comments of the operator1 user account. Remove the operator3 user from the system.
</h3>

<hr>

<h1>
    Solution :
</h1>

<h5>Lab 1:</h5>
<p></p>
<p>1. Open the terminal and type:</p>
<i>sudo useradd operator1</i>
<br>

<img width="483" alt="Screenshot 2025-03-26 at 2 39 06 PM" src="https://github.com/user-attachments/assets/968ac413-3c78-4a55-a909-d5c4d5697902" />
<p> </p>

<p>2. To check whether or not the user is added:</p>
<i>sudo cat /etc/passwd</i>
<br>

<p>3. To add the password:</p>
<i>sudo passwd operator1</i>
<br>
<img width="478" alt="Screenshot 2025-03-26 at 2 46 02 PM" src="https://github.com/user-attachments/assets/2a63da65-27ac-416e-b32e-ba0b8035c152" />

<p> </p>
<p>4. Follow the same steps for operator2 and operator3 as well:</p>
<br>
<img width="498" alt="Screenshot 2025-03-26 at 2 51 15 PM" src="https://github.com/user-attachments/assets/82a483f4-5a95-46bb-862b-55d3c9a129d1" />

<h5>Lab 2:</h5>
<p>1. To add comments to a particular user, type:</p>
<i>sudo usermod -c "Operator1's comment" operator1</i>
<br>
<img width="712" alt="Screenshot 2025-03-26 at 2 55 21 PM" src="https://github.com/user-attachments/assets/0bcda434-b22e-4c72-a943-473024386ea2" />

<p>2. To delete the user:</p>
<i>sudo userdel -r operator</i>
<br>
<img width="556" alt="Screenshot 2025-03-26 at 2 58 51 PM" src="https://github.com/user-attachments/assets/5e32c4c5-599e-4215-bd24-24605e95587a" />

<h5>Creating Practice Files and Directories:</h5>
<p>Use the <i>touch</i> command to create sets of empty practice files:</p>
<i>touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi</i>

<p>Use a single command to create all three subdirectories:</p>
<i>mkdir friends family work</i>
<img width="731" alt="Screenshot 2025-03-26 at 3 04 21 PM" src="https://github.com/user-attachments/assets/7d2bf2c0-0330-4faa-b417-231a194e5241" />

