# Language
FROM javascript:3.9-alpine

# Work Directory
WORKDIR /main

# Put the content in the Work Directory
COPY . /main

# Installing the dependencies
RUN npm install --no-cache-dir --upgrade -r requirements.txt

# Command that will run
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "81"]