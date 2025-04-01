# PDF_form_fill
This is a small project to automate PDF form filling using the intelligence of Vision Language Model
The idea is to fill the form when the field inputs can't be matched with the actual form labels. For example let us consider Sai Srinivas is a 26 year old male and is single. The input JSON may look like this
![image](https://github.com/user-attachments/assets/b7e123e0-10fb-4fa9-a69d-f30a1d3d5e14)


Below is the sample form to be filled
![image](https://github.com/user-attachments/assets/1267c406-e6ad-424c-8b9a-053c01f92038)

As you observe, here the labels are not exactly matching with the input values (for example 26 year old would be considered as ≥18), but we expect the output to be something like below
![image](https://github.com/user-attachments/assets/616e1cf4-4d1f-41fc-955d-c5c88728fa3c)

