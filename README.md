# 08-ansible-04
# Установка стека clickhouse - vector - lighthouse:

>	1) установить зависимости из файла requirements.yml
>		ansible-galaxy install -r requirements.yml
>	2) заполнить inventory файл /inventory/prod.yml и запустить playbook:
>		ansible-playbook -i inventory/prod.yml site.yaml
>
>	Playbook основан на ролях и устанавливает и настраивает:
>	- clickhouse
>	- nginx (нужен для работы lighthouse)
>	- vector
>	- lighthouse
