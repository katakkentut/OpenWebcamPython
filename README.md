# Open Webcam

Python Transmitting and Receiving Video Camera Using Socket


## Module Used

```python
imutils==0.5.4
opencv_python==4.6.0.66
```
## Usage


### Install All Module

```python
  pip install -r requirements.txt
```
### Run Tool

```python
  #receiver side
  python receiver.py
  
  #sender side
  python sender.py
```

### Convert To EXE

```python
  # Using Pyinstaller
  Pyinstaller --noconfirm --onefile sender.py

  # recommend Using Nuitka
  py -m nuitka --mingw64 .\sender.py --standalone --onefile 
 ```
 
 
 
