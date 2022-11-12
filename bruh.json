async function handleRequest(request) {
  //const views = await KV.get("views");

  //await KV.put("views", parseInt(views) + 1);
  
  return new Response(html, {
    headers: {
      'content-type': 'text/html;charset=UTF-8',
    },
  });
}

addEventListener('fetch', event => {
  return event.respondWith(handleRequest(event.request));
});