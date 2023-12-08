Edit the NoGuidance.java file in ./fuzz/src/main/java/edu/berkeley/cs/jqf/fuzz/random


Default runs part 3(branch decisions).



TO RUN PART 4(all trace events + integer 200):

Uncomment the generateCallBack() method (with the "part 4" comment above it)
Comment out the generateCallBack() method (with the "part 3" comment above it)
Edit the getInput() method, uncomment "200" and comment out "random.nextInt(256)"

