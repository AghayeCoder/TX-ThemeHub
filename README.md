# TX-ThemeHub
TX-UI Panel Subscription Page Templates Designed By TX Community.
## Usable Variables:

| Variable    | Description                                   |
|------------|-----------------------------------------------|
| `result`   | Returns the URI for Vmess/Vless.             |
| `total`    | Returns the formatted total traffic.         |
| `expire`   | End date as a timestamp.                     |
| `upload`   | Returns the formatted uploaded traffic.      |
| `download` | Returns the formatted downloaded traffic.    |
| `totalByte` | Returns the total traffic in bytes.        |
| `uploadByte` | Returns the total uploaded traffic in bytes. |
| `downloadByte` | Returns the total downloaded traffic in bytes. |
| `sId`      | Returns the subscription user ID.           |
| `subUrl`   | Gets the full subscription URL.             |

**example**
```html
<div>sub url is : {{ .subUrl }}</div>
```
## Steps to Implement:

1. Design an HTML page and name it **sub.html**.  
2. Move the file to the following directory:  
   ```
   /etc/x-ui/html/
   ```
3. Go to the panel settings, navigate to the **Subscription** section, and enable the **Custom Template** option.  
4. Save the changes and restart the service.  

If everything is done correctly, your custom template should now be displayed instead of the default subscription page.
