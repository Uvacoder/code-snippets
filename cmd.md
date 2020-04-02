```bash
# screencapture (capture images from screen)
# Take screenshot & save it to Desktop with current date as name
screencapture -ixoa -t jpg ~/"Desktop/$(date).jpg"
```

```bash
# docker (run processes in isolated containers)
# Delete all containers
for i in $(docker ps -a -q); do docker rm $i; done

# List all containers
docker ps -a

# Remove a container after it’s stopped
docker run --rm [...]
```

```bash
# kubectl (run commands against Kubernetes clusters)
# Get info on pods in use. Has info on why they failed if they did.
kubectl describe pods

# Get services across all namespaces
kubectl get svc --all-namespaces

# Port forward the <pod> from 5432 to localhost 5300 port
kubectl port-forward <pod> 5300:5432
```

```bash
# nix-env (manipulate or query Nix user environments)
# See installed packages
nix-env -q

# Install packages
nix-env -iA
```

```bash
# basename (strip directory and suffix from filenames)
basename "/Users/nikivi/Documents/books/Thinking, fast and slow.pdf" # => Thinking, fast and slow.pdf
```

```bash
# chmod (change file mode bits)
# All users can read and write but cannot execute
chmod 666

# All actions for all users
chmod 777

# Only owner can do all actions; group and other users are allowed only to read
chmod 744
```

```bash
# tail (output the last part of files) https://www.explainshell.com/explain/tail
# Shows the last 10 lines of file
tail /etc/passwd

# -n option allows to change the number of lines to display
# where n is the number of lines you want to see
# ie
tail -5 /etc/passwd

# Use tail +n to print lines starting at line n
```

```bash
# playgo (send .go file to the Go Playground) https://github.com/plutov/playgo
# Open Go playground of file in browser
playgo <file>
```

```bash
# tr (translate or delete characters) https://www.explainshell.com/explain/tr
# Convert all input to upper case
ls | tr a-z a-z

# Take the output and put into a single line
ls | tr  "\n" " "

# Get rid of all numbers
ls -lt | tr -d 0-9
```

```bash
# diff (compare files line by line) https://www.explainshell.com/explain/diff
# Compare file1 with file2
diff file1 file2
```

```bash
# find (walk a file hierarchy) https://www.explainshell.com/explain/find
# Will search in current directory (.) for the file 'hello_world.py'
# and will return the path to the file
find . -name 'hello_world.py'

# You can also search multiple directories
# will search both Documents and Desktop folders for the file
find Documents Desktop -name 'hello_world.py'
```

[grep](https://www.explainshell.com/explain/grep) (file pattern searcher)

```bash
# Print lines from a file or input stream that match an expression

# -i = case insensitive search

# -v = return all lines that do not contain {}
grep -v {} story.txt
```
