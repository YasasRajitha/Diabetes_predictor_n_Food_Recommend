# Diabetes_predictor_n_Food_Recommend
This is my Final Year Project.
This includes an app that can predict diabetes by Glucose level, Insulin dose, BMI, Age and also Recommend Foods by cooking time, and calorie content.

## How to start this web application
1. Install ansible.
```shell
sudo apt install ansible
```

2. Run ansible playbook.
```shell
ansible-playbook -K playbook.yml
```
Note : "Download necessary csvs" task might take long , Because it is over 300MB s.

3. Visit application through http://localhost:85 .