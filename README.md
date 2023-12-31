# stack

Proof of concept for building app with multiple serverless function on vercel

Validate multiple serverless functions and advantages of different technology stacks

Check out [Serverless Functions Overview | Vercel Docs](https://vercel.com/docs/concepts/functions/serverless-functions) for more details.

<div style=" color: #00FA9A; padding: 10px;">
<p>Initially, using src/app directory failed, serverless function API proxy  and custom directory support was not available. </p> 
 <p>Therefore, I switched to a structure similar to the rust-runtime demo.
 and for now, I am testing WebAssembly.</p>
</div>
<br> 
<br>

![cover](./public/snapshot/2023-8-5.png)

## Deploy on Vercel

<div style=" color: #FFA500; padding: 10px;">
<!--   <strong> ⚠️ NOTICE:</strong>  -->
 WASM will not be updated, and the test code has no correlation.
 
 [The reason for the directory( /api, /pages/api, /fn )](https://github.com/orgs/vercel/discussions/3495) is to find a way to combine multiple serverless functions, and I am still trying and waiting for more possibilities.
 
</div>
<br>

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/fromwhite/stack&project-name=stack&repository-name=stack)

Or

<a href="https://github.com/fromwhite/stack/fork">
  <img src="https://github.com/fluidicon.png" alt="GitHub Logo" width="30"  >
</a>
<br> 
<br>

Check out [Deploying GitHub Projects with Vercel](https://vercel.com/docs/concepts/deployments/git/vercel-for-github) for more details.
