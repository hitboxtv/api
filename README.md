The hitbox API enables you to develop your own applications using the feature set that we provide.

## Formats
The base URL for all API resources is <code>http://api.hitbox.tv/</code>

## Index

**[[media|Media]]**

| **Endpoint** | **Description**        |
| [[media|GET /media ]]      | Get livestream media object        |

**[[user|User]]**

| **Endpoint** | **Description**        |
| [[user|GET /user ]]      | Get user object        |

**[[games|Games]]**

| **Endpoint** | **Description**        |
| [[games|GET /games ]]      | Get channel object        |

**[[teams|Teams]]**

| **Endpoint** | **Description**        |
| [[teams|GET /teams ]]      | Get list of active team objects       |
| [[teams|GET /:team ]]      | Get team object        |

**[[token|Token]]**

| **Endpoint** | **Description** |
| [[token|POST /auth/token ]] | Get the authentication-token |

**[[ingesting|Ingesting]]**

| **Endpoint** | **Description**        |
| [[ingesting|GET /streamingest/:media_name ]]      | Get ingest informations       |
