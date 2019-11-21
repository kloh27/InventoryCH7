# InventoryCH7

Instructions to Use the Playbook.


## 
# 
# Condition "AND" - Both condition must be met.
# Example:
#    when: ansible_facts['distribution'] == "Microsoft Windows Server 2016 Core" and
#          ansible_facts['architecture'] == "64-bit"
#
# Condition "OR" - IF the first condition is true then it will not check the one. If it 
#    not true, then it will keep checking for the correct value.
# Example:
#    when: ansible_facts['distribution'] == "Microsoft Windows Server 2016 Core" or
#          ansible_facts['architecture'] == "64-bit"
#
# Condition "OR" and "AND" - Example: A or B and C. It will check A or B (choose the right one)
#   then check the vaulue C.
#
# Multiple Conditions 
#   
# Complex Conditions
#  (condition1 = value OR Condition2 = value) And (condition1 = value OR Condition2 = value)
#  (condition1 = value OR Condition2 = value) Or (condition1 = value OR Condition2 = value)
#  (Architecture and Distribution) AND (Date or Month) OR Major version
#
###








