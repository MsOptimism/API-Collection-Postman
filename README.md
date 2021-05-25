
**Log in** (Functional)
***

Field | Check | Notes
---------|----------|---------
 *E-mail* |  | 
  smoke | default state | 
  critical pass | existing email | 
  critical pass | not existing email| 
  critical pass | incorrect existing email| 
  critical pass | unregistered email  | 
 critical pass | case sensitive  | 
 critical pass | empty field| 
   smoke | 1 symbol | 
 critical pass | max symbols | 
 critical pass | max+1 symbols | 
 smoke | copy, cut & paste shortcuts | 
  smoke| the context menu in the field | 
 smoke | switching between fields by "Tab" | 
 smoke | states after reloading the form | 
 smoke | enter by "Enter" | 
 *Phone number* | | 
  smoke | default state | 
  critical pass | existing phone number | 
  critical pass | not existing phone number| 
  critical pass | incorrect existing phone number| 
 critical pass  | unregistered phone number  | 
 critical pass | empty field| 
   smoke | 1 symbol | 
 critical pass | max symbols | 
 critical pass | max+1 symbols | 
 smoke | copy, cut & paste shortcuts | 
 smoke | the context menu in the field | 
  smoke| switching between fields by "Tab" | 
  smoke| states after reloading the form | 
 smoke | enter by "Enter" | 
 *"Log in" button* |  | 
 smoke | default state | 
 smoke | works | 
 extended  | multiple press | 
 smoke | "enter" with empty field "email or phone number" | 
  smoke| "enter" with empty field "password" | 
 smoke | "enter" with empty fields | 
 smoke | switching between fields by "Tab" | 
 smoke | enter by "Enter" | 



***
**Forgot password** (Functional)
***


Field | Check | Notes
---------|----------|---------
  *"Please enter your email or mobile num.." field*|  | 
  smoke | default state | 
  critical pass | existing email | 
  critical pass | not existing email| 
  critical pass | incorrect existing email| 
  critical pass | unregistered email  | 
 critical pass | case sensitive  | 
  critical pass | existing phone number | 
  critical pass | not existing phone number| 
  critical pass | incorrect existing phone number| 
 critical pass  | unregistered phone number  | 
 critical pass | empty field| 
   smoke | 1 symbol | 
 critical pass | max symbols | 
 critical pass | max+1 symbols | 
 smoke | copy, cut & paste shortcuts | 
 smoke | the context menu in the field | 
  smoke| switching between fields by "Tab" | 
  smoke| states after reloading the form | 
 smoke | enter by "Enter" | 
 *"search" button* |  | 
 smoke | default state | 
 smoke | works | 
 extended  | multiple press |  
 smoke | "enter" with empty field | 
 smoke | switching between fields by "Tab" | 
 smoke | enter by "Enter" | 
  *"cancel" button* |  | 
 smoke | default state | 
 smoke | works | 
 extended  | multiple press |  
 smoke | switching between fields by "Tab" | 
 smoke | enter by "Enter" | 



***
**Sign up** (Functional)
***


Field | Check | Notes
---------|----------|---------
 *first name* |  | 
  smoke | default state | 
 smoke | english | 
 smoke | cyrillic | 
 smoke | hierogliphs  | 
 smoke| digits | 
  smoke | special characters | 
 smoke | empty field |  
 smoke | 1 symbol | 
 critical pass | max symbols | 
 critical pass | max+1 symbols | 
 smoke | copy, cut & paste shortcuts | 
  smoke| the context menu in the field | 
 smoke | switching between fields by "Tab" | 
 smoke | states after reloading the form | 
 smoke | enter by "Enter" | 
 *last name* |  | 
   smoke | default state | 
 smoke | english | 
 smoke | cyrillic | 
 smoke | hierogliphs  | 
 smoke| digits | 
  smoke | special characters | 
 smoke | empty field |  
 smoke | 1 symbol | 
 critical pass | max symbols | 
 critical pass | max+1 symbols | 
 smoke | copy, cut & paste shortcuts | 
  smoke| the context menu in the field | 
 smoke | switching between fields by "Tab" | 
 smoke | states after reloading the form | 
 smoke | enter by "Enter" | 
  *E-mail* |  | 
  smoke | default state | 
  critical pass | existing email | 
  critical pass | not existing email| 
  critical pass | incorrect existing email| 
   smoke | english | 
 smoke | cyrillic | 
 smoke | hierogliphs  | 
 smoke| digits | 
  smoke | special characters | 
 critical pass | case sensitive  | 
 critical pass | empty field| 
  smoke | 1 symbol | 
 critical pass | max symbols | 
 critical pass | max+1 symbols | 
 smoke | copy, cut & paste shortcuts | 
  smoke| the context menu in the field | 
 smoke | switching between fields by "Tab" | 
 smoke | states after reloading the form | 
 smoke | enter by "Enter" | 
 *Phone number* | | 
  smoke | default state | 
  critical pass | existing phone number | 
  critical pass | not existing phone number| 
  critical pass | incorrect existing phone number| 
   smoke | english | 
 smoke | cyrillic | 
 smoke | hierogliphs  | 
 smoke| digits | 
  smoke | special characters | 
 critical pass | empty field| 
  smoke | 1 symbol | 
 critical pass | max symbols | 
 critical pass | max+1 symbols | 
 smoke | copy, cut & paste shortcuts | 
 smoke | the context menu in the field | 
  smoke| switching between fields by "Tab" | 
  smoke| states after reloading the form | 
 smoke | enter by "Enter" | 
 *re-enter e-mail* |  | 
  smoke | default state | 
 critical pass | the same email | "e-mail" field
   critical pass | different email | "e-mail" field
  critical pass | existing email | 
  critical pass | not existing email| 
  critical pass | incorrect existing email| 
   smoke | english | 
 smoke | cyrillic | 
 smoke | hierogliphs  | 
 smoke| digits | 
  smoke | special characters | 
 critical pass | case sensitive  | 
 critical pass | empty field| 
  smoke | 1 symbol | 
 critical pass | max symbols | 
 critical pass | max+1 symbols | 
 smoke | copy, cut & paste shortcuts | 
  smoke| the context menu in the field | 
 smoke | switching between fields by "Tab" | 
 smoke | states after reloading the form | 
 smoke | enter by "Enter" | 
  *birthday* |  | 
  smoke | default state | 
 smoke | works | 
  | input consistency checks | dates in the future, etc.
  | leap year check | 
  smoke| states after reloading the form |  
 *gender* |  | 
  smoke | default state | 
  | functionality  | (on / off)
  | more than 1 radio button cannot be enabled | 
  | one radio button should be enabled | 
  smoke| states after reloading the form | selected radio button should not be reset 
   *"custom" gender choose*| | 
  | "select your pronoun" dropdown | possible to choose
  *"gender(optional)" field*|  | 
  smoke | default state | 
 smoke | english | 
 smoke | cyrillic | 
 smoke | hierogliphs  | 
 smoke| digits | 
  smoke | special characters | 
 smoke | empty field |  
 smoke | 1 symbol | 
 critical pass | max symbols | 
 critical pass | max+1 symbols | 
 smoke | copy, cut & paste shortcuts | 
  smoke| the context menu in the field | 
 smoke | switching between fields by "Tab" | 
 smoke | states after reloading the form | 
 smoke | enter by "Enter" | 
 *"sign up" button* |  | 
 smoke | default state | 
 smoke | works | 
 extended  | multiple press | 
 smoke | "enter" with empty field "first name" | 
  smoke | "enter" with empty field "last name" | 
  smoke | "enter" with empty field "phone number" | 
   smoke | "enter" with empty field "e-mail" |   smoke | "enter" with empty field "re-enter e-mail" | 
  smoke| "enter" with empty field "password" | 
 smoke | "enter" with default field "birthday" | 
   smoke | "enter" with empty field "gender" |
 smoke | "enter" with empty fields | 
 smoke | switching between fields by "Tab" | 
 smoke | enter by "Enter" | 




		
