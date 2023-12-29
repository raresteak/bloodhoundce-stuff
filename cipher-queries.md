# Cipher queries

## Domain users with dangerous privledges to domain groups.
```
MATCH p=(m:User)-[:Owns|Self|AllExtendedRights|WriteDacl|GenericAll|WriteOwner|ExecuteDCOM|GenericWrite|AllowedToDelegate|ForceChangePassword]->(n:Group)
RETURN p
```

## Domain users with dangerous privledges to other domain users
```
MATCH p=(m:User)-[:Owns|Self|AllExtendedRights|WriteDacl|GenericAll|WriteOwner|ExecuteDCOM|GenericWrite|AllowedToDelegate|ForceChangePassword]->(n:User)
RETURN p
```
