UTDStatus
=========


===================================================== ======================================================================================================================
Значения                                              Описание
===================================================== ======================================================================================================================
OutboundWaitingForSenderSignature                     документ исходящий, документ не отправлен, поскольку не подписан отправителем
OutboundWaitingForInvoiceReceiptAndRecipientSignature документ исходящий, от покупателя ожидается извещение о получении УКД, ответная подпись, либо отказ от ее формирования
OutboundWaitingForInvoiceReceipt                      документ исходящий, ожидается извещение о получении УКД от покупателя
OutboundWaitingForRecipientSignature                  документ исходящий, ответная подпись, либо отказ от ее формирования еще не получены
OutboundWithRecipientSignature                        документ исходящий, ответная подпись получена
OutboundRecipientSignatureRequestRejected             документ исходящий, получен отказ от формирования ответной подписи
OutboundInvalidSenderSignature                        документ исходящий, документ не отправлен, поскольку подпись отправителя не является корректной
OutboundFinished                                      документ исходящий, документооборот завершен
OutboundNotFinished                                   документ исходящий, извещение о получении УКД от покупателя уже есть, но документооборот еще не завершен
InboundWaitingForRecipientSignature                   документ входящий, ответная подпись, либо отказ от ее формирования еще не отправлены
InboundWithRecipientSignature                         документ входящий, ответная подпись поставлена
InboundRecipientSignatureRequestRejected              документ входящий, отправлен отказ от формирования ответной подписи
InboundInvalidRecipientSignature                      документ входящий, документооборот не завершен, поскольку подпись полуателя не является корректной
InboundNotFinished                                    документ входящий, документооборот не завершен
InboundFinished                                       документ входящий, документооборот завершен
UnknownDocumentStatus                                 неизвестный статус
===================================================== ======================================================================================================================
