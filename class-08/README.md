# Access Control (ACL)

## Review, Research, and Discussion

1. 
    * **Basic Authentication:** is used when signing up/in to encode/decode when signing up and encrypt/decrypt the password when saving/reading the password in/from the database.
    * **Bearer Authentication:** is used when you want to stay logged in by using token, or when you want to give a permission to use access your account data in another service by an access limited token.

2. It's secure data delivery service that uses tokens to get permission to access account data also when providing it you don't need to go through sign in process every time depending on the expiring data of that token.

3. That no one has access to it except for the server that verifies the access token.
    

### Terms

**Encryption:** Changing the way something is written to the point where it becomes unreadable and hard to decrypt it by adding symbols, numbers, and letters.

**Token:** Key that gives you permission to access something.

**Bearer:** Authentication method, it uses token in order to give permission for accessing data.

**Secret:** Secret token it's used for verifying access token, it must be kept so now one accesses it except for the server that runs the verification process.

**JSON Web Token:** It's secure data delivery service that uses tokens to get permission to access account data also when providing it you don't need to go through sign in process every time depending on the expiring data of that token.

<hr>

## RBAC

It stands for Role Based Access Control, which means that applying rules or policies for some users to either to limit or give them full access over the data.