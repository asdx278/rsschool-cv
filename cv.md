![foto](https://github.com/asdx278/rsschool-cv/blob/gh-pages/IMG_1815.JPG)
# Personal Details
 **First name:** _Albert_  
 **Second name:** _Shubin_  
 **Date of birth:** _27.07.1989_  
 **email:** _albert.shubin@gmail.com_  
 **telephone:** _+7 912 345 67 89_  
 **Country:** _Russia_, **city:** _Saratov_
# Education
 **University**: _Chernyshevsky N.G. Saratov State University, Faculty of Computer Science and Information Technologies, Department of System Analysis and Automatic Control, Master’s degree (2017-2019)_
# Work experience
 **[Gazprom UGS Ltd.](https://ugs.gazprom.ru/)**  
 _2009-presen; Saratov, Russia;  
 System Administrator_  
 **Responsibilities:**  
* administration:  
  * Microsoft Exchange Server 2003/2019
  * Microsoft Windows Servers 2012/2016/2019 (AD, DNS, DHCP, WSUS);  
* technical support for users:  
  * SAP/1C/DocsVision/CryptoPRO/MS Office
# Example of code
```
function calc(value) {      
    if (value.match(/=|Enter/)) {  
        try {  
            output.textContent = Math.trunc(math.evaluate(output.textContent))  
        } catch {              
            let oldValue = output.textContent              
            let newValue = 'недопустимое выражение'            
            output.textContent = newValue            
            setTimeout(() => {
                output.textContent = oldValue
            }, 1500)
        }    
    } else if (value === 'C') {        
        output.textContent = ''    
    } else if (value.match(/CE|Backspace/)) {    
        output.textContent = output.textContent.substring(0, output.textContent.length - 1)    
    } else {         
        output.textContent += value
    }
} 
```
# English language
A2