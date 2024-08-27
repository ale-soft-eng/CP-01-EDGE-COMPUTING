## Engenharia de Software - 2º SEMESTRE  
## Disciplina:  EDGE COMPUTING 
### Integrantes:  
Alexandre Assis do Nascimento - RM: 558927  
Gustavo Ramalho Gaudêncio - RM: 554582  

## Checkpoint 01: Dashboard Metereológico no NodeRED com Integração ao Arduíno  

A primeira etapa da atividade consistiu em utilizar a API do Open Weather e criar o flow de dados no NodeRED.  
Criamos 2 flows, um para cada cidade: São Paulo e Belo Horizonte  
![image](https://github.com/user-attachments/assets/ebbd974e-b026-4075-85af-d3cbb4c4a564)

Pegamos as informações do clima de cada cidade:  
- Temperatura (em Fahrenheit)
- Pressão
- Nível do Mar
- Nível das Núvens

Como resultado, nosso dashboard ficou assim:  
![image](https://github.com/user-attachments/assets/03964db6-616e-4a0d-8853-ac25ee831c6e)

![image](https://github.com/user-attachments/assets/ebcaecf5-3539-4390-9af1-995569565be4)

A segunda etapa da atividade consistiu em montar o circuito do Arduíno e fazer o código para que ele funcionasse.  
Componentes usados ao montar o arduíno:  
- Arduíno Uno
- Protoboard
- Cabos Jumpers
- Sensor ultrassônico

Circuito montado:
![image](https://github.com/user-attachments/assets/9274ff3e-3247-4f42-9d91-43fcbc9506dd)
![image](https://github.com/user-attachments/assets/a4206540-6ec8-4eb0-b547-55a86bbea71c)

Como resultado o código ficou dessa forma:  
![image](https://github.com/user-attachments/assets/8b7ef4e1-caa2-4fc3-824b-aef6ce420c60)  

E por fim, realizamos a integração entre o Arduíno e o NodeRED. Com isso, foi possível ver os níveis de distância oscilando:  
![image](https://github.com/user-attachments/assets/80d37f30-1ad0-4d99-86f8-5db86ab88440)




