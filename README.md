    $ bundle

start and open with:

    $ foreman start
    $ open http://localhost:4567/

## using lang strings with placeholders example

    explain_subselection_button: "Der Button %{button} lässt dich detailliertere Versandkosten pro Land einstellen."

    = t('shipping.explain_subselection_button', :button => "<span class='shipping-blabla'>df</span>")  
