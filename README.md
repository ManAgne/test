# Mano pirmoji GIT repozitorija

## Repositorijos pasiuntimas
    git clone <repozitorijos-nuoroda>

## Pagrindinės komandos
    git add -> failų paruošimas patvirtinimui
        git add <failo-pavadinimas> -> prideda failą nurodytu pavadinimu
        git add . -> Prideda visus pakitusius failus

    git diff -> skirtumas tarp dviejų failų, ar dviejų to paties failo versijų
        git diff <failo pavadinimas> -> failo nurodytu pavadinimu pakitmai nuo paskutinio commit'o

    git status -> parodo pakitusių failų būseną

    git branch -> komanda, kuri naudoja operacijas su šakomis
        git branch -a -> parodo visas parsiųstas šakas ir šiuo metu aktyvią šaką

    git commit -> komanda skirta užtvirtinti projekto pakitimus
        git commit -m "Žinutė apibūdinanti pakitimą"

    git push -> komanda skirta paviešinti commit'us į atitinkamą globalią šaką