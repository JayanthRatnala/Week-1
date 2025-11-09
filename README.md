# Week-1
// -- IDENTITY (🚨 don't commit real tokens/SSIDs) --
#define BLYNK_TEMPLATE_ID "TMPL3T0JOfLs_"
#define BLYNK_TEMPLATE_NAME "SmartGuard Home Automation"
#define BLYNK_AUTH_TOKEN "Q9-qayLQVk2Sg7PDE_0MSGAckDawX00H"
// -- LIBS --
#include <Wire.h>
#include <LiquidCrystal_I2C.h>
#include <WiFi.h>
#include <BlynkSimpleEsp32.h>
// -- LCD CONFIG --
#define LCD_ADDR 0x27
LiquidCrystal_I2C lcd(LCD_ADDR, 16, 2);
// -- PIN DEFINITIONS --
#define ACS_PIN     34
#define LED1_PIN    26
#define LED2_PIN    25
#define FAN_PIN     27
#define SW_LED1     13
#define SW_LED2     14
#define SW_FAN      12
#define BUZZER_PIN  33 
