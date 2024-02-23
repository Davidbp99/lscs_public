For blogs and other logs system use below:

**Server Hook**

LSCS:ForcePowerUsed

Args: ply, item (is a table so you can grab anything from your force powers. Example item.PrintName)


--------------------
**Server Hook**

LSCS:ForcePowerEnded

Args: ply, item (is a table so you can grab anything from your force powers. Example item.PrintName)


--------------------
Permission check below:

**Server Hook**

LSCS:AllowedForce

Args: ply, item (is a table so you can grab anything from your force powers. Example item.PrintName)

Return: true, false, fallsback to true

--------------------
**Client Hook**

LSCS:AllowedMenu

Args: ply

Return: true,  false, fallshack to true
