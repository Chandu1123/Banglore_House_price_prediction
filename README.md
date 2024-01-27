# Banglore_House_price_prediction
# End to END project___Prediction of house prices in bangalore 

# Project flow



1.install requirements.txt file

2.data_cleaning.ipynb


nginx is used for the dynamic link(localhost)

How to execute :
 
 1) Install nginx
 2) make the below changes nginx conf file 
    	location /api/ {
		rewrite ^/api(.*) $1 break;
		proxy_pass http://127.0.0.1:5000;
	}



