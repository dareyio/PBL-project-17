# install graphviz 
sudo apt install graphviz

# use the command below to generate dependency graph
- terraform graph -type=plan | dot -Tpng > graph.png
- terraform graph  | dot -Tpng > graph.png

# Read Morew abot terrafrom graph
https://www.terraform.io/docs/cli/commands/graph.html