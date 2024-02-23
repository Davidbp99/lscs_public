For blogs and other logs system use below:

LSCS:ForcePowerUsed

Args: ply, item (is a table so you can grab anything from your force powers. Example item.PrintName)

Server Hook
--------------------
LSCS:ForcePowerEnded

Args: ply, item (is a table so you can grab anything from your force powers. Example item.PrintName)

Server Hook
--------------------
Permission check below:

LSCS:AllowedForce

Args: ply, item (is a table so you can grab anything from your force powers. Example item.PrintName)

Return: true, false, fallsback to true

Server Hook
--------------------
LSCS:AllowedMenu

Args: ply

Return: true,  false, fallshack to true

Client Hook
