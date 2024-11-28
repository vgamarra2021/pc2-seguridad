pip install -r requirements.txt
sed 's/^."\(.\)".$/\1/g' f03.html | grep http | sed 's/\?.$//' > output.txt