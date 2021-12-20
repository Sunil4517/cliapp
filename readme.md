# step-1:
    * imported the requirements i.e, modules which we want below are the modules we imported
        1). requests
        2). json
        3). argparse
        4). csv
        Note: requests should be installed by using command "pip install requests" and no need for remaining

# step2
    * used the RestApi url provided by NIST CVE to retrive wanted info like CVE ID, Published Date, First Reference URL, English Description
    and printing it into cves.csv file. 
    * Here we get the info from API in Json format so we format the Json into Json String and this String into python dictionary to access the key value pairs in python easily. 

# step3
    * Finally when we execute this python file in command line we must use an argument "getcve" (no need of double quotes).