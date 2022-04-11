# Mano pirmoji GIT repozitorija

Ši repozitorija skirta tam, kad išmokti naudotis **projektų versijavimo kontrolės komandinės eilutės sąsaja - GIT CLI**. Tam jums reikės parsisiųsti ir įsirašyti:
https://git-scm.com/downloads

## Repositorijos pasiuntimas

1. Atsidarykite GIT CLI (GIT bash).
2. Naudodamiesi komanda &lt;cd&gt; pakeistkite savo darbinę kategoriją į tą, kurioje norite parsisiųsti repozitoriją
3. Parsiųskite repozitoriją:
    git clone &lt;repozitorijos-nuoroda&gt; (i.e. https://github.com/ManAgne/test)
4. Pakeiskite darbinę kategoriją į parsiųstos repozitorijos kategoriją
    cd test
    

## Pagrindinės komandos
- **git add** -> failų paruošimas patvirtinimui
- **git add &lt;failo-pavadinimas&gt;** -> prideda failą nurodytu pavadinimu
        **git add .** -> Prideda visus pakitusius failus

- **git diff** -> skirtumas tarp dviejų failų, ar dviejų to paties failo versijų
    - **git diff &lt;failo-pavadinimas&gt;** -> failo nurodytu pavadinimu pakitmai nuo paskutinio commit'o

- **git status** -> parodo pakitusių failų būseną

- **git branch** -> komanda, kuri naudoja operacijas su šakomis
    - **git branch -a** -> parodo visas parsiųstas šakas ir šiuo metu aktyvią šaką

- **git commit** -> komanda skirta užtvirtinti projekto pakitimus
    - **git commit -m "Žinutė apibūdinanti pakitimą"**

- **git push** -> komanda skirta paviešinti commit'us į atitinkamą globalią šaką