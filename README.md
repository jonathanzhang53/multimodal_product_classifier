# Multimodal Product Classifier

https://gist.github.com/GinoAvanzini/f0ed9c1a74ffce3f832c9fa68f19daba

## Virtual Environment

1. `python -m venv virtual_env`
2. `source virtual_env/Scripts/activate`
3. `pip install -r requirements.txt`
   
   a. `pip freeze --local > requirements.txt` when you're adding a new package

3. `deactivate`

## Data

1. Download [abo-images-small.tar](https://amazon-berkeley-objects.s3.us-east-1.amazonaws.com/index.html)
2. Extract `/images/small` to `/images/small`
3. These images will be ignored in commits and should be loaded in on an individual basis
4. Metadata about the images and listings are stored in the repository itself