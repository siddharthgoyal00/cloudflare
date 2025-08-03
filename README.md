# cloudflare  

package.json (dev dependencies)
"vitest": "~3.2.0",	 // unit tesing 
"wrangler": "^4.26.0" // CLi(command line interface) for the cloud flare 

where is the express code ? http server 
cloud flare expect to just write the logic to handle request 
creating httpserver are handled by the cloudflare 

how can i do routing ?
we can do in cloudflare but we will use the external liberaries 
hono(best like a express) , itty-router ,  worktop(by cloudflare devs  )


to deploy the application on the cloud flare :-
npx wrangler login 
npx wrangler whoami
npm run deploy 

