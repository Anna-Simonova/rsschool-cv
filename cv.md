## **[rsschool-cv](https://anna-simonova.github.io/rsschool-cv/cv)**
# **Anna Simonova**
## Contact Information
**Phone:** +375(29)561-56-31  
**E-mail:** asyarabpochta@gmail.com\
**Telegram:** @simonovaanya\
## About Yourself
I finished the first course of BNTU. I want to try to develop into frontend and hope that it will be my passion. The university gave many opportunities to try themselves in backend, but it did not give fully show themselves. I hope to gain a good knowledge in frontend and develop myself by becoming better.
## Skills:
* HTML
* CSS
* JavaScript

## Code Examples
Sample code from my final project on Stepik
```
checkboxElement.forEach((checkbox, index) => {
    const input = inputElement[index];

    input.disabled = true;
    input.value = '0';

    checkbox.addEventListener('change', function() {
        if (this.checked) {
            input.disabled = false;
            input.value = '1';
        } else {
            input.disabled = true;
            input.value = '0';
        }
        calculateTotal();
    })

    input.addEventListener('input', function() {
        if(this.value < '0'){
            this.value = '0';
        }
        if(this.value === '0'){
            checkbox.checked = false;
            this.disabled = true;
        }
        calculateTotal();
    })
});
```
## Education
* **Belarusian National Technical University**
  * Software Engineering
## Languages
* Russian - Native
* English - A1~A2(Severe case..)

