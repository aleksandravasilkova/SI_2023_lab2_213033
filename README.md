Aleksandra Vasilkova 213033


Control Flow Graph

![CFGraph](https://github.com/aleksandravasilkova/SI_2023_lab2_213033/assets/129284068/68e4a4b4-b9c0-4b6b-be46-5cc7e811ba2b)

Цикломатска комплексност
Имам 11 цикломатска комплексност што ја увидов според затворени региони + 1 надворешен исто така истата ја увидов и со броење на условите

тест случаи според критериумот Every branch
За every branch се потребни 5 test case

тест случаи според Multiple Condition критериумот
if (user==null || user.getPassword()==null || user.getEmail()==null)
има случај кога user !=null значи имаме Тrue натакај не не занима што се условите затоа што крајно if условот е исполнет поради или логичкиот знак (Т,х,х)
случај кога user == null , но password != null повторно е исполнет условот и не не интересира шти ќе биде емаилот (F,T,x)
случај кога user и password се Null, но емаил е !=null повтороно if Условот е исполнет (F,F,T)
и последниот случај кога сите се null  и if условот нема да биде исполнет т.е ќе биде false (F,F,F)








