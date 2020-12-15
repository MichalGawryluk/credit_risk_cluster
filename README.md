# credit_risk_cluster

1. **Classic credit scoring** - biorę okno czasowe np.: 3M i dla każdego takiego okna sprawdzam, czy kontrakt płacił, czy nie, jak zaczął niepłacić to robię default i na pdst. zmiennej binarnej robię model prawdopodobieństwa deafaltu.
Dane kontraktowe
2. **Dynamic credit scoring** - interesuje mnie przewidywany rozkład spłaconych rat dla każdego kontraktu w czasie. Powoli zaczynamy myśleć bardziej w kontekście wartościowym, niż prawd. W momencie zawarcia umowy ratalnej generowany jest harmonogram. Każdą ratę rozpatrujemy w kontekście zapłaconej lub niezapłaconej. Wówczas możemy dla każdego kontraktu policzyć liczbę niezapłaconych należności w czasie. A zatem możliwym jest stworzenie wartości ryzyka kredytowego (wielkość złego długu) w czasie.
Dane kontraktowe + Dane fakturowe 
Niezbędne dane (kontrakty_id, fakutra_id, data_wystawianie, transakcja_id, data_zaplaty należności)
