Description of attached files

Input data:
    weather_24h.txt - full 24-hour data used to evaluate compression algorithms; subsets with 1, 2, 3, 4, 6, 8 and 12 hours of data can be obtained by trimming this file appropriately:
        1h - first 3300 bytes
        2h - first 6600 bytes
        3h - first 9900 bytes
        4h - first 13200 bytes
        6h - first 19800 bytes
        8h - first 26400 bytes
        12h - first 39600 bytes

Oscillograms:
    Measurements of time and current required to compress the data of given size
    (channel 1 [yellow] - current measured as voltage drop across the 1 ohm shunt resistor, channel 2 [cyan] - time)
        Canonical Huffman algorithm - huffman_[weather data size].png
            huffman_1h.png
            huffman_2h.png
            huffman_3h.png
            huffman_4h.png
            huffman_6h.png
            huffman_8h.png
            huffman_12h.png
            huffman_24h.png
        LZ77 algorithm - lz77_[weather data size].png
            lz77_1h.png
            lz77_2h.png
            lz77_3h.png
            lz77_4h.png
            lz77_6h.png
            lz77_8h.png
            lz77_12h.png
            lz77_24h.png
        LZ78 algorithm - lz78_[weather data size].png
            lz78_1h.png
            lz78_2h.png
            lz78_3h.png
            lz78_4h.png
            lz78_6h.png
        LZW algorithm (without map) - lzw_no_map_[weather data size].png
            lzw_no_map_1h.png
            lzw_no_map_2h.png
            lzw_no_map_3h.png
            lzw_no_map_4h.png
        LZW algorithm (with map) - lzw_with_map_[weather data size].png
            lzw_with_map_1h.png
            lzw_with_map_2h.png
            lzw_with_map_3h.png
        JPEG algorithm - JPEG_[image size].png
            JPEG_160x120.png
            JPEG_320x240.png
            JPEG_640x480.png
    Measurements of FS1000A module transmission speed
    (channel 1 [yellow] - data received, channel 2 [cyan] - data sent)
        Full frame - FS1000A_[baud rate]_frame.png
            FS1000A_2kbps_frame.png
            FS1000A_4kbps_frame.png
            FS1000A_5kbps_frame.png
            FS1000A_10kbps_frame.png
        Part of the frame containing data - FS1000A_[baud rate]_data_in_frame.png
            FS1000A_2kbps_data_in_frame.png
            FS1000A_4kbps_data_in_frame.png
            FS1000A_5kbps_data_in_frame.png
            FS1000A_10kbps_data_in_frame.png
    Measurements of time and current required to prepare ESP-01 for transmission
    (channel 1 [yellow] - current measured as voltage drop across the 1 ohm shunt resistor, channel 2 [cyan] - time)
        ESP8266_boot.png - Boot device
        ESP8266_connect.png - Connect to AP
        ESP8266_get_ip.png - Get IP address with DHCP
        ESP8266_estabilish_tcp.png - Estabilish TCP connection
    Measurements of time and current required to transmit the data of given size
    (channel 1 [yellow] - current measured as voltage drop across the 1 ohm shunt resistor, channel 2 [cyan] - time)
        FS1000A - FS1000A_[baud rate]_tx.png
            FS1000A_5kbps_tx.png
        nRF24L01+ - nRF24L01_[data_size]_byte(s)_frame.png
            nRF24L01_01_byte_frame.png
            nRF24L01_02_bytes_frame.png
            nRF24L01_03_bytes_frame.png
            nRF24L01_04_bytes_frame.png
            nRF24L01_05_bytes_frame.png
            nRF24L01_06_bytes_frame.png
            nRF24L01_07_bytes_frame.png
            nRF24L01_08_bytes_frame.png
            nRF24L01_09_bytes_frame.png
            nRF24L01_10_bytes_frame.png
            nRF24L01_11_bytes_frame.png
            nRF24L01_12_bytes_frame.png
            nRF24L01_13_bytes_frame.png
            nRF24L01_14_bytes_frame.png
            nRF24L01_15_bytes_frame.png
            nRF24L01_16_bytes_frame.png
            nRF24L01_17_bytes_frame.png
            nRF24L01_18_bytes_frame.png
            nRF24L01_19_bytes_frame.png
            nRF24L01_20_bytes_frame.png
            nRF24L01_21_bytes_frame.png
            nRF24L01_22_bytes_frame.png
            nRF24L01_23_bytes_frame.png
            nRF24L01_24_bytes_frame.png
            nRF24L01_25_bytes_frame.png
            nRF24L01_26_bytes_frame.png
            nRF24L01_27_bytes_frame.png
            nRF24L01_28_bytes_frame.png
            nRF24L01_29_bytes_frame.png
            nRF24L01_30_bytes_frame.png
            nRF24L01_31_bytes_frame.png
            nRF24L01_32_bytes_frame.png
        ESP8266 board - ESP8266_send_[data size]_byte(s).png
            ESP8266_send_0001_byte.png
            ESP8266_send_0002_bytes.png
            ESP8266_send_0004_bytes.png
            ESP8266_send_0008_bytes.png
            ESP8266_send_0016_bytes.png
            ESP8266_send_0032_bytes.png
            ESP8266_send_0064_bytes.png
            ESP8266_send_0128_bytes.png
            ESP8266_send_0256_bytes.png
            ESP8266_send_0512_bytes.png
            ESP8266_send_1024_bytes.png
            ESP8266_send_2048_bytes.png

