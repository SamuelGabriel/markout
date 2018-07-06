## Installation
```
pip install markout
```
## Usage
```
./something | markout
```
or
```
python main.py | markout
```
or something else with STDOUT
## Example
```
# test.py
print("## Case 1")
print ("*Result*",1)
print("______")
print("**by Sam**")
```
running
```
python test.py | markout
```
results in a Webpage showing
## Case 1
*Result* 1
_______
**by Sam**
