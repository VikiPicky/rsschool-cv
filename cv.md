## **Viktoriia Mitiakova**

Web Full-Stack Developer
_____________________________________________________________
### Education

* Algonquin College, Ontario Diploma Program in Computer Programming 
* RS School
______________________
### About

![Alt-my picture](assets\Photo.jpg)

Learning my way through to become a Web Full-Stack Developer, full English proficiency under the hood, happily worked for the World Bank and Ubisoft. 

Passinate about the way things work or trying to make them work.

On the Deans's List of Honors two semesters in a row.

________________________

### Languages:
+ Java
+ SQL (mySQL, MS Server, Oracle)
+ JavaScript
+ PHP
+ HTML / CSS
+ Android Development Basics (Java)
+ Linux, Eclipse, VS Code
+ Git Hub

__________

### Languages

   Language    | Proficiency
---------------|:-------:  
Russian        |    native
English        |    C2
French         |    A2

________
### Code Sample

![Code](https://miro.medium.com/max/800/1*nftoTHMTibmPs4gpgvhEeQ.png)

*Search Function for Online Store*

    function Search() {
      var input, filter, table, tr, td, i, j, txtValue, tableRowFitsSearchFilter;
      input = document.getElementById("myInput");
      filter = input.value.toUpperCase();
      
      table = document.getElementById("myTable");
      tr = table.getElementsByTagName("tr");
      if (filter == "") {
        for (i = 0; i < tr.length; i++) { 
            tr[i].style.display = "none";
        }
        return;
      } 

      for (i = 1; i < tr.length; i++) {
        td = tr[i].getElementsByTagName("td");
        tableRowFitsSearchFilter = false;

        for (j = 0; j < td.length; j++) {
            txtValue = td[j].textContent || td[j].innerText;
            tableRowFitsSearchFilter = txtValue.toUpperCase().indexOf(filter) > -1;
            if (tableRowFitsSearchFilter == true) {
                break
            };
        }   

        if (tableRowFitsSearchFilter == true) {
            tr[i].style.display = "";
        } else {
            tr[i].style.display = "none";
        }
      }
    }

______

### Contact:
**Phone:** +1 438 666 66666  
**E-mail:** v.mitiakova@yahoo.net  
**Git:** [VickyPicky](https://github.com/VikiPicky)
