##Problem:
 ```bash
ERROR [sensors] Accel #0 fail:  TIMEOUT!	
WARN  [health_and_arming_checks] Preflight Fail: vertical velocity unstable
ERROR [sensors] Accel #0 fail:  TIMEOUT!	
WARN  [health_and_arming_checks] Preflight Fail: vertical velocity unstable
WARN  [health_and_arming_checks] Preflight Fail: vertical velocity unstable
WARN  [health_and_arming_checks] Preflight Fail: vertical velocity unstable
ERROR [sensors] Accel #0 fail:  TIMEOUT!	
WARN  [health_and_arming_checks] Preflight Fail: height estimate not stable
ERROR [sensors] Accel #0 fail:  TIMEOUT!	
WARN  [health_and_arming_checks] Preflight Fail: vertical velocity unstable
ERROR [sensors] Accel #0 fail:  TIMEOUT!	
WARN  [health_and_arming_checks] Preflight Fail: vertical velocity unstable
ERROR [sensors] Accel #0 fail:  TIMEOUT!	
WARN  [health_and_arming_checks] Preflight Fail: height estimate not stable
WARN  [health_and_arming_checks] Preflight Fail: height estimate not stable
ERROR [sensors] Accel #0 fail:  TIMEOUT!
 ```
## Solution:
 ```bash 
 export PX4_SIM_SPEED_FACTOR=0.1
```
