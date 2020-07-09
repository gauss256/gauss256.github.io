{% include lib/mathjax.html %}
# Bootstrap your own latent (BYOL)

It is very unclear how to have $$\alpha$$ math.

$$
\mathcal{L}_{\theta}^{\mathrm{BYOL}} \triangleq\left\|\overline{q_{\theta}}\left(z_{\theta}\right)-\bar{z}_{\xi}^{\prime}\right\|_{2}^{2}=2-2 \cdot \frac{\left\langle q_{\theta}\left(z_{\theta}\right), z_{\xi}^{\prime}\right\rangle}{\left\|q_{\theta}\left(z_{\theta}\right)\right\|_{2} \cdot\left\|z_{\xi}^{\prime}\right\|_{2}}
$$

## Math seems to be working now!

For example,

$$\xi \leftarrow \tau \xi+(1-\tau) \theta$$

Do I need to put newlines before and after the math delimiters?
