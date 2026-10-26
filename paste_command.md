# Paste command

Paste this into your RunPod pod's terminal (**Connect → JupyterLab → File → New → Terminal**) and press Enter:

```bash
curl -sL https://raw.githubusercontent.com/cryptozeiss/comfyui_save_tiff16/main/setup.sh | bash
```

When it prints **DONE**:

1. In ComfyUI, click **Manager → Restart**, wait about 30 seconds, then refresh the browser.
2. Click **Workflows** in the left toolbar and open the workflow for your image.

Use the same command to update a pod that's already set up.

## With phone notifications (optional)

Install the **ntfy** app, subscribe to your own unique topic, then use this version instead, with your topic in place of `your-topic`:

```bash
curl -sL https://raw.githubusercontent.com/cryptozeiss/comfyui_save_tiff16/main/setup.sh | NTFY_TOPIC=your-topic bash
```

You'll get a message each time ComfyUI finishes its queue. See the [README](README.md#phone-notifications-optional) for details.

Full instructions are in the [README](README.md).
