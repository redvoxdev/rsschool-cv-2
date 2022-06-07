# **Maksim Ivashniou**

## **Contact information:**

**Location:** Belarus, Mogilev

**Phone:** +375295449801

**E-mail:** maksim.ivashniou@gmail.com

[Telegram](https://t.me/Maksim_Ivashniou)

[GitHub](https://github.com/MaksimIvashniou)

[LinkedIn](https://www.linkedin.com/in/maksim-ivashniou-2087191a4/)

## **About Myself:**

Hello. I'm 23 years old. I'm learning back-end development. I joined the EPAM lab in the QA department in 2019 and got an amazing teamwork experience. I went to RS School on the recommendation of an EPAM employee to improve my front-end development skills and become a good full-stack developer.

## **Skills**

### **Programming langeages:**
* С# (Advanced)
* HTML5 (Intermediate)
* CSS3 (Intermediate)
* JavaScript (Intermediate)
* TypeScript (Pre-Intermediate)

### **Frameworks, Tools:**
* .NET, .NET Core (Advanced)
* ASP.NET (Intermediate)
* Entity Framework (Intermediate)
* Angular 2+ (Pre-Intermediate)
* SQL (Pre-Intermediate)
* SSMS (Pre-Intermediate)
* Postman API (Basics)
* Git (Basics)
* JIRA (Basics)

### **Soft:**
* Good working experience based on kanban methodology
* Newcomers onboarding and adaptation

## **Code examples**
```
static uniqueLoginValidator(authService: AuthenticationService, findLikeDublicate: boolean): AsyncValidatorFn {
    return (control: AbstractControl): Observable<ValidationErrors> => {
      let data: UserAuth = {
        login: control.value
      }

      return authService.checkLogin(data)
        .pipe(
          map((result: boolean) => {
            return (result === findLikeDublicate) ? { isDboValue: true } : {}
          }));
    }
  }
```

## **Education**
* Belarussian-Russian University
    + Engineering-Economic department

## **Experience**
* QA Tester (trainee): July 2019 - April 2020

## **Cources**
* RS School Cource "JS/FE Pre-School 2022Q2" - **In progress**

## **Languages**
* Belarusian - Native
* Russian - Native
* English
    + EPAM Assessment results:
        - Writing: A2
        - Speaking: A2