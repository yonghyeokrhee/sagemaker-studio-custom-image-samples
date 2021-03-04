FROM continuumio/anaconda3
RUN pip install ipykernel && \
        python -m ipykernel install --sys-prefix
        
RUN pip install -r requirements.txt

COPY my-file.txt /root/my-file.txt
