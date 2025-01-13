ncandidates = 0
nmandates=0
candidates = []
modelist = []
mode = ""
value = []
win = []
custom = []
class hondt:
  def mode():
    global mode
    modelist = ["hondt","lague","mlague","custom"]
    print("Select mode:")
    print(modelist)
    modechange = input()
    for i in range(len(modelist)):
      if modechange == modelist[i]:
        if modechange == "custom":
          i = 0
          global custom
          custom = []
          while True:
            j = i+1
            print("Quocient",j,"is")
            buffer = input()
            if buffer == "end":
              break
            custom.append(int(buffer))
            i = i + 1
          mode = modechange
          print(custom)
          print(mode, "was selected" )
          break
        else:
          mode = modechange
          print(mode, "was selected" )
          break
    if modechange != mode:
      print("The mode wasn't selected")
  def setup():
    candidates = []
    ncandidates = input("Number of candidates is:")
    ncandidates = int(ncandidates)
    nmandates = input("Number of mandates is:")
    nmandates = int(nmandates)
    for i in range(ncandidates):
      n = i+1
      print("The candidate",n,"is:")
      candidates.append(input())
    value = []
    for  i in range(ncandidates):
      n = i+1
      print("The candidate",candidates[i],"'s value is:")
      value.append(input())
  def next():
    global win
    global truevalue
    global value
    global winner
    global mode
    global custom
    if mode == "hondt":
      j = win[winner] + 1
      truevalue[winner] = value[winner] /  j
    if mode == "lague" or mode == "mlague":
      j = win[winner] * 2 + 1
      truevalue[winner] = value[winner] /  j
    if mode == "custom":
      if len(custom) <= win[winner]:
        print("Not enough quocients, select next")
        custom.append(int(input()))
      truevalue[winner] = value[winner] /  custom[win[winner]]
  def run():
    global truevalue
    truevalue = []
    global value
    global winner 
    global win
    win = []
    if mode == "hondt" or mode == "lague":
      for i in range(ncandidates):
        truevalue.append(value[i])
        win.append(0)
    elif mode == "mlague":
      for i in range(ncandidates):
        buffer = value[i] / 1.4
        truevalue.append(buffer)
        win.append(0)
    elif mode == "custom":
      for i in range(ncandidates):
        truevalue.append(value[i] / custom[0])
        win.append(0)
    k = ncandidates-1
    for i in range(nmandates):
      winner = 0
      for i in range(k):
        l = i+1
        if truevalue[winner] < truevalue[l]:
          winner = l
        elif truevalue[winner] == truevalue[l] and win[winner] > win[l] :
          winner = l
      win[winner] = win[winner] + 1
      hondt.next()
    for i in range(len(win)):
      print(candidates[i],":", win[i])
  def test():
    global ncandidates
    ncandidates = 4
    global nmandates
    nmandates = 20
    global candidates
    candidates = ["John","Brad","Kay","Egla"]
    global value
    value = [5000,2500,2000,1000]
    global mode
    mode = "mlague"
