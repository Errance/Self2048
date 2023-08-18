fetch("https://knn3-gateway-test.api.knn3.xyz/knexus-backend/api/collections/generateImage", {
  "headers": {
    "accept": "application/json, text/plain, */*",
    "accept-language": "en-US,en;q=0.9",
    "authorization": "Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjdmMmQ4ZjgzLTNkNGEtNDZkYi1hNjFjLTdiNTgxYmFkMGNjMSIsImFkZHJlc3MiOiIweGQzNDIwYTNiZTBhMWVmYzBmYmQxM2U4NzE0MWM5N2IyYzlhYzlkZDMiLCJlbWFpbCI6Ind5NTAzOTQ1OTMwQGdtYWlsLmNvbSIsIm51bSI6IjUyNzU4OTMiLCJuYW1lIjpudWxsLCJkZXNjcmlwdGlvbiI6bnVsbCwiY291cG9uIjo4MSwiaW1hZ2UiOm51bGwsImNyZWF0ZWRfYXQiOiIyMDIzLTA4LTExVDEyOjEzOjMwLjAwMFoiLCJ1cGRhdGVkX2F0IjoiMjAyMy0wOC0xMVQxMjoxMzozMC4wMDBaIiwiaXNfd2FpdF9saXN0IjowLCJpc19maXJzdCI6MCwiZm9sbG93ZXJfY291bnQiOjAsImZvbGxvd2VlX2NvdW50IjowLCJpYXQiOjE2OTIzNTExODEsImV4cCI6MTY5MjUzMTE4MX0.Cl0k9W4nm-UE5NYsguzF3Vz5G7OiZ3EGqGk0waXqNfE",
    "content-type": "application/json",
    "sec-ch-ua": "\"Not/A)Brand\";v=\"99\", \"Google Chrome\";v=\"115\", \"Chromium\";v=\"115\"",
    "sec-ch-ua-mobile": "?0",
    "sec-ch-ua-platform": "\"macOS\"",
    "sec-fetch-dest": "empty",
    "sec-fetch-mode": "cors",
    "sec-fetch-site": "same-site"
  },
  "referrer": "https://knexus.staging.knn3.xyz/",
  "referrerPolicy": "strict-origin-when-cross-origin",
  "body": "{\"positive_prompt\":\"1\",\"negative_prompt\":\"(NSFW:-1), paintings, sketches, fingers, (worst quality:2), (low quality:2), (normal quality:2), lowres, normal quality, ((monochrome)), ((grayscale)), skin spots, acnes, skin blemishes, age spot, (outdoor:1.6), backlight,(ugly:1.331), (duplicate:1.331), (morbid:1.21), (mutilated:1.21), (tranny:1.331), mutated hands, (poorly drawn hands:1.5), blurry, (bad anatomy:1.21), (bad proportions:1.331), extra limbs, (disfigured:1.331), (more than 2 nipples:1.331), (missing arms:1.331), (extra legs:1.331), (fused fingers:1.61051), (too many fingers:1.61051), (unclear eyes:1.331), lowers, bad hands, missing fingers, extra digit, (futa:1.1),bad hands, missing fingers, bad-hands-5\",\"sampling_method\":\"DPM++ 2M Karras\",\"style\":\"\",\"style_key\":\"Anime 2.5D\",\"checkpoint\":\"Anime_2.5D.safetensors\",\"sampling_steps\":20,\"cfg_scale\":\"7\",\"seed\":-1,\"size\":\"1:1\",\"control_net\":false,\"control_img\":\"\",\"preprocessor\":\"\",\"performance\":\"0\",\"model\":\"\",\"weight\":\"0\",\"pattern\":\"master\"}",
  "method": "POST"
});
