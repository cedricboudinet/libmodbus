MDFILES = \
        modbus_close.md \
        modbus_connect.md \
        modbus_flush.md \
        modbus_free.md \
        modbus_get_byte_from_bits.md \
        modbus_get_byte_timeout.md \
        modbus_get_float.md \
        modbus_get_float_abcd.md \
        modbus_get_float_badc.md \
        modbus_get_float_cdab.md \
        modbus_get_float_dcba.md \
        modbus_get_header_length.md \
        modbus_get_response_timeout.md \
	modbus_get_slave.md \
        modbus_get_socket.md \
        modbus_mapping_free.md \
        modbus_mapping_new.md \
        modbus_mapping_new_start_address.md \
        modbus_mask_write_register.md \
        modbus_new_rtu.md \
        modbus_new_tcp_pi.md \
        modbus_new_tcp.md \
        modbus_read_bits.md \
        modbus_read_input_bits.md \
        modbus_read_input_registers.md \
        modbus_read_registers.md \
        modbus_receive_confirmation.md \
        modbus_receive.md \
        modbus_reply_exception.md \
        modbus_reply.md \
        modbus_report_slave_id.md \
        modbus_rtu_get_serial_mode.md \
        modbus_rtu_set_serial_mode.md \
        modbus_rtu_get_rts.md \
        modbus_rtu_set_rts.md \
        modbus_rtu_set_custom_rts.md \
        modbus_rtu_get_rts_delay.md \
        modbus_rtu_set_rts_delay.md \
        modbus_send_raw_request.md \
        modbus_set_bits_from_bytes.md \
        modbus_set_bits_from_byte.md \
        modbus_set_byte_timeout.md \
        modbus_set_debug.md \
        modbus_set_error_recovery.md \
        modbus_set_float.md \
        modbus_set_float_abcd.md \
        modbus_set_float_badc.md \
        modbus_set_float_cdab.md \
        modbus_set_float_dcba.md \
        modbus_set_response_timeout.md \
        modbus_set_slave.md \
        modbus_set_socket.md \
        modbus_strerror.md \
        modbus_tcp_accept.md \
        modbus_tcp_pi_accept.md \
        modbus_tcp_listen.md \
        modbus_tcp_pi_listen.md \
        modbus_write_and_read_registers.md \
        modbus_write_bits.md \
        modbus_write_bit.md \
        modbus_write_registers.md \
        modbus_write_register.md

MANPAGES = $(MDFILES:%.md=%.man)
manpages : $(MANPAGES)
.md.man:
	pandoc  $< -s -o $@ -t man
CLEANFILES =  *.man
