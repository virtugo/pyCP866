import subprocess

p = subprocess.Popen('dir c:\', shell=True, stdout = subprocess.PIPE)
out = p.stdout.read()
print (out.decode('CP866'))
