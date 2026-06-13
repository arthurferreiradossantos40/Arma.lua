print("Arma de Sorte")
print("Chance de tiro: 60%")
print("Chance de explosão: 40%")
print("Girando a sorte...")

local chance = math.random(1, 100)

if chance <= 60 then
    print("RESULTADO: A arma atirou")
else
    print("RESULTADO: A arma explodiu")
end