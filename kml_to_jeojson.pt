# install togeojson before running this code
def kml_to_geojson(filepath):
    kml_list=os.listdir(filepath)
    only_names=[]
    for names in kml_list:
        name=os.path.splitext(os.path.basename(names))[0]
        only_names.append(name)
    print(only_names)
    for names in only_names:
        os.system("togeojson"+" "+filepath+"/"+names+".kml"+">"+" "+names+".geojson")
"""not working"""
def clean_filenames(filepath):
    for filename in filepath:
        print filename
        os.rename(filename, filename.replace(" ", "_"))
