---
layout: post
title:  "XML"
date:   2020-05-19 20:46:01 +0200
categories: jekyll update
---
<?xml version="1.0" encoding="UTF-8"?>
<Measurement id="condition_insomnia">
  <title language="EN">Insomnia</title>
  <title language="FR">Insomnie</title>
  <title language="ES">Insomnio</title>
  <description language="EN">Enables you to check sleep behavior and associated attributes.</description>
  <description language="FR">Permet de vérifier le comportement du sommeil et les attributs associés.</description>
  <description language="ES">Le permite comprobar el comportamiento del sueño y atributos asociados.</description>
  <quantityMeasurementTypes>
    <quantityMeasurementType id="SLEEP_SLEEPAMOUNT" precision="4" scale="1">
      <quantity id="SLEEPAMOUNT_QTYID" standardUnit="SLEEPAMOUNT_STDUNIT_HR">
        <title language="EN">Sleep Amount</title>
        <title language="FR">Somme du sommeil</title>
        <title language="ES">Cantidad de sueño</title>
        <units>
          <unit id="SLEEPAMOUNT_STDUNIT_HR" />
          <unit id="SLEEPAMOUNT_STDUNIT_MIN" />
        </units>
      </quantity>
      <globalRanges>
        <upperNormalValue value="9">
          <title language="EN">Upper Normal</title>
          <title language="FR">Valeur normale supérieure</title>
          <title language="ES">Valor normal superior</title>
        </upperNormalValue>
        <lowerNormalValue value="6">
          <title language="EN">Lower Normal</title>
          <title language="FR">Valeur normale inférieure</title>
          <title language="ES">Valor normal inferior</title>
        </lowerNormalValue>
        <hypoValue value="2">
          <title language="EN">Hypo</title>
          <title language="FR">Hypo</title>
          <title language="ES">Hipo</title>
        </hypoValue>
      </globalRanges>
    </quantityMeasurementType>
    <quantityMeasurementType id="SLEEP_HEARTRATE" precision="3" scale="0">
      <quantity id="HEARTRATE" standardUnit="HEARTRATE_STDUNIT_BPM">
        <title language="EN">Heart rate</title>
        <title language="FR">Rythme Cardiaque</title>
        <title language="ES">Ritmo Cardiaco</title>
        <units>
          <unit id="HEARTRATE_STDUNIT_BPM" />
        </units>
      </quantity>
      <globalRanges>
        <upperNormalValue value="80">
          <title language="EN">Upper Normal</title>
          <title language="FR">Valeur normale supérieure</title>
          <title language="ES">Valor normal superior</title>
        </upperNormalValue>
        <lowerNormalValue value="60">
          <title language="EN">Lower Normal</title>
          <title language="FR">Valeur normale inférieure</title>
          <title language="ES">Valor normal inferior</title>
        </lowerNormalValue>
        <hyperValue value="100">
          <title language="EN">Hyper</title>
          <title language="FR">Hyper</title>
          <title language="ES">Hiper</title>
        </hyperValue>
        <hypoValue value="50">
          <title language="EN">Hypo</title>
          <title language="FR">Hypo</title>
          <title language="ES">Hipo</title>
        </hypoValue>
      </globalRanges>
    </quantityMeasurementType>
  </quantityMeasurementTypes>
  <categoryMeasurementTypes>
    <categoryMeasurementType id="SLEEP_TYPEOFSLEEP" entriesPerMeasurement="1">
      <title language="EN">Type of Sleep</title>
      <title language="FR">Type de sommeil</title>
      <title language="ES">Tipo de sueño</title>
      <categoryMeasurementItems>
        <categoryMeasurementItem id="TYPEOFSLEEP_VALUE_RESTLESSSLEEP" orderIndex="1">
          <title language="EN">Restless Sleep</title>
          <title language="FR">Sommeil agité</title>
          <title language="ES">Sueño inquieto</title>
        </categoryMeasurementItem>
        <categoryMeasurementItem id="TYPEOFSLEEP_VALUE_GOODSLEEP" orderIndex="2">
          <title language="EN">Good sleep</title>
          <title language="FR">Bien sommeil</title>
          <title language="ES">Buen sueño</title>
        </categoryMeasurementItem>
        <categoryMeasurementItem id="TYPEOFSLEEP_VALUE_DEEPSLEEP" orderIndex="3">
          <title language="EN">Deep Sleep</title>
          <title language="FR">Sommeil profound</title>
          <title language="ES">Sueño profundo</title>
        </categoryMeasurementItem>
      </categoryMeasurementItems>
    </categoryMeasurementType>
    <categoryMeasurementType id="SLEEP_ENVIRONMENT" entriesPerMeasurement="2">
      <title language="EN">Environment</title>
      <title language="FR">Environnement</title>
      <title language="ES">Ambiente</title>
      <categoryMeasurementItems>
        <categoryMeasurementItem id="ENVIRONMENT_VALUE_HUMID" orderIndex="1">
          <title language="EN">Humid</title>
          <title language="FR">Humide</title>
          <title language="ES">Húmedo</title>
        </categoryMeasurementItem>
        <categoryMeasurementItem id="ENVIRONMENT_VALUE_COLD" orderIndex="2">
          <title language="EN">Cold</title>
          <title language="FR">Du froid</title>
          <title language="ES">Frío</title>
        </categoryMeasurementItem>
        <categoryMeasurementItem id="ENVIRONMENT_VALUE_HOT" orderIndex="3">
          <title language="EN">Hot</title>
          <title language="FR">Chaud</title>
          <title language="ES">Caliente</title>
        </categoryMeasurementItem>
        <categoryMeasurementItem id="ENVIRONMENT_VALUE_QUIET" orderIndex="4">
          <title language="EN">Quiet</title>
          <title language="FR">Silencieux</title>
          <title language="ES">Tranquilo</title>
        </categoryMeasurementItem>
        <categoryMeasurementItem id="ENVIRONMENT_VALUE_NOISY" orderIndex="5">
          <title language="EN">Noisy</title>
          <title language="FR">Bruyant</title>
          <title language="ES">Ruidoso</title>
        </categoryMeasurementItem>
      </categoryMeasurementItems>
    </categoryMeasurementType>
  </categoryMeasurementTypes>
</Measurement>