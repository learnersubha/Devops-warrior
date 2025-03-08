1. View the content of a file and display line numbers.
 => if you inly want to show file contant then you can use cat commant
cat test.txt  # test is the file name
![Screenshot from 2025-03-08 16-12-06](https://github.com/user-attachments/assets/3427ee12-bc12-4543-87cb-9339488e8dee)

    If you  want to show file with line numbers then use nl
    nl test.txt
![Screenshot from 2025-03-08 16-20-36](https://github.com/user-attachments/assets/3c2731d9-7de1-4e6a-b002-fc31f5ab5c54)

2. Change the access permissions of files to make them readable, writable, and executable by the owner only.
=> chmod is the command to change file permission, for this question answer is sudo chmod 700 filename
![Screenshot from 2025-03-08 16-25-32](https://github.com/user-attachments/assets/65a580da-2f90-48b7-96a5-95aaff77ef29)

 3. Check the last 10 commands you have run.
 => history | head
![Screenshot from 2025-03-08 16-30-41](https://github.com/user-attachments/assets/dc40a571-0a82-46e5-b8b8-27e73d799c03)

4. Remove a directory and all its contents.
=> rm -r directory name
 ![Screenshot from 2025-03-08 16-34-40](https://github.com/user-attachments/assets/6afee704-1e54-485d-9add-e922b4e0f973)

 5. Create a fruits.txt file, add content (one fruit per line), and display the content.
 => use vim command to create the file fruit.txt vim fruit.txt
    with echo command add one fruit in every line  {echo "mango"}
    ![Screenshot from 2025-03-08 16-40-00](https://github.com/user-attachments/assets/9e816948-aed0-46f5-97ef-849a6ad91c4b)
    ![Screenshot from 2025-03-08 16-40-19](https://github.com/user-attachments/assets/6af93846-5a62-424b-8dd5-b93162712b1c)

 6. Add content in devops.txt (one in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava. Then, append "Pineapple" to the end of the file.
 => echo -e "Pineapple" devops.txt
 ![Screenshot from 2025-03-08 16-51-04](https://github.com/user-attachments/assets/9f0eac3a-97c9-40ba-a687-4a004305b370)

  7. Show the first three fruits from the file in reverse order.
  => head -3 devops.txt | tac
  ![Screenshot from 2025-03-08 16-54-43](https://github.com/user-attachments/assets/65023115-b6d7-4681-98da-ac4f2bf59e30)

   8. Show the bottom three fruits from the file, and then sort them alphabetically.
   => for bottom three tail -3 devops.txt  | tac
  ![Screenshot from 2025-03-08 16-57-13](https://github.com/user-attachments/assets/809bd53e-7b1b-4e5e-8f45-98f4577d4b62)

      sort alphabetically sort -t= devops.txt
![Screenshot from 2025-03-08 17-04-07](https://github.com/user-attachments/assets/2b6c5f9a-cf72-4917-a081-7214e9cd3cdf)

  9. Create another file Colors.txt, add content (one color per line), and display the content.Add content in Colors.txt (one in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey. Find and display the lines that are common between fruits.txt and Colors.txt.
      comm -12 devops.txt colors.txt 
 10. Count the number of lines, words, and characters in both fruits.txt and Colors.txt.
  => wc -l # for count line
     wc -w # for count word
     ec -c # for count charactor
     ![Screenshot from 2025-03-08 17-20-49](https://github.com/user-attachments/assets/eaae2c16-6eb3-4369-aeaa-8ac50584fe1f)

















