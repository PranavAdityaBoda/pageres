it('captures a car screenshot', async () => {
  const pageres = new Pageres();
  const url = 'https://example.com/car';
  const options = { timeout: 30, crop: true };

  await pageres.captureCarScreenshot(url, options);

  expect(pageres.#items.length).toBe(1);
  expect(pageres.#items[0].filename).toBe('car-screenshot.png');
});