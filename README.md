# Spotify List Lang
Spotify artist database by singing language, with link, name and Spotify ID.

## Properties :

**Name** : *The name of the artist.*  
**Id** : *The Spotify id of the artist.*  
**Lang_main** : *The primary language in which the artist sings. The origin of a singer/band has no impact. If it is a mainly instrumental artist it will be noted "None".*  
**Lang_alt** : *A list of secondary languages in which the artist can sing. Only really significant languages are listed. If an artist has sung once in Spanish and 50 times in English, they will be marked as English, but the Spanish will not be noted. However, if an artist sings a significant number, such as ten songs out of 50 songs, in Spanish, this will be noted.*  

## Example

```json
{
    "name": "Michael Jackson",
    "id": "3fMbdgg4jU18AjLCKBhRSm",
    "lang_main": "en",
    "lang_alt": [""]
}
```