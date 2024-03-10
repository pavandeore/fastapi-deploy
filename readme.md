
to install packages -> pip3 install fastapi uvicorn  --break-system-packages
to start app -> uvicorn main:app --host=0.0.0.0 --port=8000

to install packages on VM -> sudo apt install python3 python3-pip
to craete process & run it in background -> nohup uvicorn main:app --host=0.0.0.0 --port=8000 &
to get process Id -> pgrep -f 'uvicorn main:app'
to kill process -> kill process_id
