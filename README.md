# Horasde30em30minutos
# Você pode executar esse script em python e ele mostrará a hora atual a cada 30 minutos
import datetime
import time

while True:
    current_time = datetime.datetime.now()
    print("Hora atual:", current_time.strftime("%H:%M:%S"))
    time.sleep(30 * 60)
