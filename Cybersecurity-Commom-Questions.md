# System Administration
## How do you change your DNS settings in Linux/Windows?
### On windows, from command line, start netsh >  
```cmd
interface show interface 
interface ip set dns name="ADAPTER-NAME" source="static" address="X.X.X.X"
```