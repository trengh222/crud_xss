# crud_xss
The CRUD backend management system has an XSS vulnerability.
As shown in the image, enter the XSS code:
<img width="1193" alt="image" src="https://github.com/user-attachments/assets/21f74bb4-7260-4f82-8a5d-f1e01b1b42e4" />
Click confirm, and then click edit again:
<img width="704" alt="image" src="https://github.com/user-attachments/assets/0aaa3634-e6fa-4948-a95c-dce158e67ef5" />
As shown in the image, trigger a pop-up. Return to the user management section and click add:
<img width="1034" alt="image" src="https://github.com/user-attachments/assets/cc42ae85-7602-4659-a06f-c8549619b01d" />
A pop-up can also be triggered here.


