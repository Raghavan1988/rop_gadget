# rop_gadget

### python compare_rop.py few_shot.txt gadget1.txt gadget2.txt 
#### Please enter your OPEN AI API KEY to continue: <<Enter your OPEN AI API KEY>>


##### {
#####  "is_rewrite": true, 
#####  "reason": "The two gadgets are rewrites of one another because they have the same sequence of operations and perform the same function.", <br>
#####  "comparison": "Line 1: Both gadgets write a value to a memory address\n\nLine 2: GADGET1 writes the value from %rax, while GADGET2 writes the value from %r13\n\nLine 3: Both gadgets zero out the %rax register\n\nLine 4: GADGET2 transfers control to the next gadget in the ROP chain, while GADGET1 uses the 'ret' instruction to transfer control" <br>
#### }

