# m5stackS3


#include <M5Unified.h>
#include "image.h"

void setup() {
  auto cfg = M5.config();
  M5.begin(cfg);

  M5.Display.setRotation(0);
  M5.Display.fillScreen(BLACK);

  M5.Display.drawPng(_1_png, _1_png_len, 0, 0);
}

void loop() {
  M5.update();
}
