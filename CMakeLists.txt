idf_component_register(SRCS "main.cpp"
                       INCLUDE_DIRS "."
                       PRIV_REQUIRES esp_wifi esp_event nvs_flash esp_netif mqtt lwip)
