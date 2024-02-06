# handshaker - Handshake quick apply bot made using Selenium

A script that automatically applies to jobs for me. Web scrapes the BYU Handshake website when you search for any job and applies to all the jobs with quick apply. Written in Python using Selenium.

## Usage

```
python script.py -q "Web developer"
python script.py -u "<username>" -p "<password>" -q "%5B%5D=3&job.salary_types%5B%5D=1"
```

`-q` or `--query` is the flag where you can enter the job you're interested in.
