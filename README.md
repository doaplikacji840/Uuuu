
import requests
    
url = "https://zylalabs.com/api/1713/routing+bank+number+checker+api/1326/routing+number+lookup?number=121000248"
    
headers = {
    'Authorization': 'Bearer 4380|xCQ72DraaFTY996m8gAbJ5R3zruo90i7gKqvXU5y'
}
    
response = requests.request("GET", url, headers=headers, data=payload)
    
print(response.text)
    
